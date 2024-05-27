Building a React Native App with Styled Text and Bold Name
Importing Required Modules
------------------------------------------------------
StatusBar is imported from expo-status-bar to manage the app’s status bar.
React is imported to utilize JSX and React components.
StyleSheet, Text, and View are imported from react-native to create styled components.

Main App Component
The App function serves as the main component of the application. It returns a View component styled with styles.container. Inside this View, there is a Text component displaying the desired text. The StatusBar component is included to enable automatic styling of the status bar.

Styles
styles.container: Defines the primary styling for the View component:
flex: 1: Makes the view fill the entire screen.
backgroundColor: Sets the background color to a specific RGB value.
alignItems: 'center': Centers the content horizontally.
justifyContent: 'center': Centers the content vertically.
fontSize: 24: Sets the font size for the text within the container.
styles.bolden: Defines the styling for the boldened text:
fontWeight: "bold": Makes the text bold.





