# Flutter In-class Exercise: My Profile Screen

This project implements the "My Profile" screen shown in the exercise handout:
an avatar with a green verified badge, a divider, and three labelled fields
(Name, Email, Points) followed by a floating "+" action button.

## Prerequisites
1. Clone this repository to your local machine.
2. Run `flutter pub get` in your terminal to fetch dependencies.
3. Ensure you have an emulator running, a physical device connected, or use
   Chrome (`flutter run -d chrome`) for a quick preview.

## Run it
```
flutter pub get
flutter run
```

## What's implemented
- Black `AppBar` titled "My Profile"
- Circular avatar placeholder with a green check badge (top layer via `Stack`)
- `Name`, `Email` (with icon), and `Points` (with star icon) fields, each bold
  label over its value
- Black `FloatingActionButton` with a "+" icon

## Submission steps
1. Make sure this repository is **public** on GitHub.
2. Push all changes:
   ```
   git init
   git add .
   git commit -m "My Profile screen implementation"
   git branch -M main
   git remote add origin <YOUR_NEW_REPO_URL>
   git push -u origin main
   ```
3. Copy the repository URL into `Submission_Template.docx`.
4. Rename that Word document to your student index number.
5. Upload the renamed document to the designated submission area.
