# Login Form 

The project implements login form. There is no functionality and only UI is implemented, and app is not actually validating/executing login (i.e., nothing happens if you press Submit button)

### Some advice:
- Implement first basic UI with required fields (without icons)
- You may implement state variables for username and password, although values 
are not required/used since app does not perform actual login
- Use parameters such as color, textAlign, fontSize etc. to modify appearance of 
Text
- Use proper keyboard options for outlined textfields (email and password)
- Use modifiers to define width, padding, etc. for components
- Add icons for textfields. Check out how to add trailing icon on [Trailing icon example](https://semicolonspace.com/jetpack-compose-textfield/), example uses email 
and lock icons
- Modify password field to display “dots” instead of actual characters using VisualTransformation. Instructions can be found on [@here](https://stackoverflow.com/questions/65304229/toggle-password-field-jetpackcompose.)Test out, that you can run app on emulator or real device and UI is visible as expected.
