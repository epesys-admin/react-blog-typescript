# Blog Application with React JS & TypeScript

# Note
	* Custom hook must starts from "use" prefix => useAuth, useLocalStorage, etc
	* Custom context must ends with Context postfix => AuthContext, ThemeContext, etc
	* Custom Component & its folder should be named in Pascal case => Button, FormButton, 

# Folder structure to follow:
	* src
		* assets
			* img
			* css
				* common.css
		* components
			* Button
				* index.ts
				* Button.component.tsx
				* Button.module.css
				* Button.type.ts
			* Input
				* index.ts
				* Input.component.tsx
				* Input.module.css
				* Input.type.ts
		* hooks
			* useAuth.ts
			* useLocalStorage.ts
		* context
			* AuthContext.ts
		* layout
			* sidebar
				* index.tsx
				* index.module.css
			* protected
				* index.tsx
				* index.module.css
			* public
				* index.tsx
				* index.module.css
		* data
			* constants.ts
		* routes
			* private-routes.tsx
			* public-routes.tsx
		* pages
			* dashboard
				* index.tsx
				* index.module.css
			* login
				* index.tsx
				* index.module.css
			* reset-password
				* index.tsx
				* index.module.css
		* utils
	* App.tsx
