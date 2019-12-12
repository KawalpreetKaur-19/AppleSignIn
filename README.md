# AppleSignIn
A demo project to implement apple sign in.    
Step 1: Target-> Signing & Capabilities -> + Capability -> Sign In Apple(Need to add it).    
Step 2: Add the below lines of code in Info.plist.
``` <key>com.apple.developer.applesignin</key>    
	<array>   
		<string>Default</string>
	</array> ```   

 Step 3: Implement the code given.    
 Note: It is mandatory that the account being used for apple sign in must have enabled two way authentication.
