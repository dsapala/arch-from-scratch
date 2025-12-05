https://youtu.be/YC7NMbl4goo?si=X7RJN1sSN9f8N-k5

a heads up: I do not encrypt the boot partition in this video, which means your keyfile can be compromised using another live ISO image.

If you want to be extra secure, skip the step for putting the keyfile in the FILES=() line in the mkinitcpio.conf This does mean you'll have to enter your password twice, however.

I have another video in the pipeline where we'll be looking at different options for securing the boot partition in this setup as there are a few options to achieve this each with their own caveats!