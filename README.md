# Gallery-App-iOS# 
Gallery App A SwiftUI gallery app using MVVM. 
Features Google Sign-In, paginated online images, offline access, and a profile page.
## Features 
- Google Sign-In
  - Paginated image gallery (e.g., Picsum API)
    - Offline image storage (SwiftData)
    - Profile page with logout
## Setup 
1. Clone the repo.
2. Add GoogleSignIn via Swift Package Manager.
   https://github.com/google/GoogleSignIn-iOS.git
   
4. Set up Google credentials.
5.  Build and run in Xcode 15+.
 ## Structure - 
 `AuthSignInSignUpVM.swift`: Auth logic 
 - `GalleryImage.swift`: Image model
 -  `ImageService.swift`: Image fetching/caching
- `GalleryViewModel.swift`: Gallery logic
- `HomeView.swift`: Gallery UI
- `ProfileView.swift`: Profile UI
## Usage - Sign in with Google. - Browse and cache images.

## License MIT
