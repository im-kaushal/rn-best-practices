## React Native Best Code Practices

1. **Exception Handling**: Use try/catch blocks for all API block codes and error boundaries. 
   - Links: [Medium Article](https://rossbulat.medium.com/react-native-working-with-error-boundaries-2ac213977383), [Mindbowser Article](https://www.mindbowser.com/how-to-implement-error-boundaries-in-react-native/)

2. **Proper Comments**: Put proper comments on each code functionality.

3. **README Maintenance**: Maintain a proper README file.

4. **Avoid Inline Styling**: Instead, use style sheets.

5. **Code Reusability**: Try to reuse the same components of the code.

6. **Release Build Best Practice**: Avoid putting console logs in the release build.

7. **Use Safe Area View**: Ensure content doesn't overlap system UI elements.
   - Link: [React Navigation Docs](https://reactnavigation.org/docs/handling-safe-area/)

8. **Keyboard Avoidance**: Use the Keyboard Avoidance View to adjust the layout when the keyboard is present.
   - Link: [LogRocket Blog](https://blog.logrocket.com/keyboardawarescrollview-keyboardavoidingview-react-native/)

9. **Code Review**: Review your code at least once before creating a pull or merge request.

10. **Imports Order**: Maintain a consistent order for imports.

11. **Naming and Layout Conventions**: Follow good naming and layout conventions.
   - Link: [Medium Article](https://sandeeprajbhartechgeek.medium.com/coding-standards-and-good-practice-for-react-native-apps-c8401e87f2d)

12. **Version Control (Git)**: Learn and use Git for version control.
   - Link: [Git Official Website](https://git-scm.com/about)

13. **Use SVG Icons**: Prefer SVG icons over PNG for scalability.

14. **Use Flatlist**: Reduce memory consumption with Flatlist instead of .map or scroll view.

15. **Maintain Constants File**: Store strings, images, colours, and themes in a constants file.

16. **State Management**: Use state management libraries like Redux.

17. **Avoid Prop Drilling**: Use context or Redux to avoid passing props through many layers.

18. **Pagination for Large Data**: Implement pagination for large data in Flatlist.

19. **Axios Wrapper for Error Handling**: Use a common Axios wrapper for error handling in APIs.

20. **Asynchronous Image Loading**: Use async concepts for loading images.
    - Link: [React Native Coach Blog](https://blog.reactnativecoach.com/creating-an-asynchronous-loading-image-component-in-react-native-part-i-1b087d0ded62)

21. **Custom Scripts**: Write custom scripts in the package.json file.
    - Link: [LogRocket Blog](https://blog.logrocket.com/everything-you-need-know-about-react-scripts/)

22. **Network Handling Wrapper**: Maintain a network handling wrapper over the application.

23. **Avoid Committing Node Modules**: Exclude node modules from version control.

24. **Environment Configuration File**: Create an environment configuration file.

25. **Memoization**: Use memoization for caching components and functions.

26. **Navigation Helper Class**: Create a navigation helper class.
27.  **Folder Structure**:


28. **Firebase Service Class**: Create a Firebase service class.

29. **Store Sensitive Data**: Ensure sensitive data is stored securely.
    - Link: [React Native Documentation](https://reactnative.dev/docs/security)

