# image_scanner
Attempt to create a simple image signing, verification and validation solution 

Proposed workflow:- 
1. Creating signatures- Create an image signature as user A
2. Tag and Sign an image as user A
3. Push image to a trusted repository - Allow definition of this custom repository eg harbor, docker
## Use case: Scenario 1
4. Making signature available to another user B to pull the image
   - Securely store/share the public key used for signing 
## Use case: Scenario 2 
   Create a web hook that created a policy definion that restricts unsigned images from spawning pods
