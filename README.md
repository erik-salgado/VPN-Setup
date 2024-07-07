![What-is-VPN-image](https://github.com/erik-salgado/VPN-Setup/assets/173113320/06702375-9484-42cc-8e14-c5cee28e88be)

# VPN Setup
In this tutorial, we're going to set up VPN from within our Virtual Machine and see how Remote Desktop Protocol Works.

# Resources needed for this Lab:
- Resource Group (Microsoft Azure)
- Virtual Machine (Windows 10 Pro)

# Operating System Used
- Windows 10 Pro

# Steps:

- Create Resource Group (Microsoft Azure)

![Screenshot 2024-07-06 173439](https://github.com/erik-salgado/VPN-Setup/assets/173113320/2f288f5a-fb14-42ca-b8b9-a0c54c21c25b)
![Screenshot 2024-07-06 173500](https://github.com/erik-salgado/VPN-Setup/assets/173113320/f92d11cc-a148-4ced-a4fc-699ad65ebafe)
![Screenshot 2024-07-06 173512](https://github.com/erik-salgado/VPN-Setup/assets/173113320/4596b10d-a359-4229-8d27-0efa03fb4f7a)
![Screenshot 2024-07-06 173526](https://github.com/erik-salgado/VPN-Setup/assets/173113320/7c2f9e13-2b76-4767-9555-cbe06c105851)

- Create Virtual Machine (Microsoft Azure). Observations: Place VM in the Resource Group you've created. Make sure the region is different from your actual location. For the Operating System choose Windows 10 pro. For the size choose 2 CPUs. Create a username and password. Review-Create Virtual Machine.

![Screenshot 2024-07-06 174040](https://github.com/erik-salgado/VPN-Setup/assets/173113320/828b3606-b9fe-4a1e-a474-a93fd457fc90)
![Screenshot 2024-07-06 174049](https://github.com/erik-salgado/VPN-Setup/assets/173113320/a1fca5df-a7c1-4add-b3a7-fb19aa293909)
![Screenshot 2024-07-06 174437](https://github.com/erik-salgado/VPN-Setup/assets/173113320/c1fb012c-c583-4548-9c0c-68677de59009)
![Screenshot 2024-07-06 174706](https://github.com/erik-salgado/VPN-Setup/assets/173113320/31904c7c-9873-42b7-93bc-dca4c34708ff)
![Screenshot 2024-07-06 174849](https://github.com/erik-salgado/VPN-Setup/assets/173113320/2d314d88-3b16-4286-a7af-d6d19f6bcd88)
![Screenshot 2024-07-06 175429](https://github.com/erik-salgado/VPN-Setup/assets/173113320/270c11e5-d6cb-44b1-8183-780852ef7e14)

- Connect to VM using RDP (Remote Desktop Protocol) Observations: Select yes for the certification.

![Screenshot 2024-07-06 175449](https://github.com/erik-salgado/VPN-Setup/assets/173113320/219a4cae-a912-4782-a46f-2c1eed6bc76f)
![Screenshot 2024-07-06 175505](https://github.com/erik-salgado/VPN-Setup/assets/173113320/a6e10528-75e8-4e8e-b51b-1873cb6e402b)
![Screenshot 2024-07-06 175536](https://github.com/erik-salgado/VPN-Setup/assets/173113320/526d04e2-a1fe-42b7-97e7-a107f4fb52b2)

- Go to www.whatismyipaddress.com inside your VM. Observations: For the sake of this lab I chosed the region to be in Europe (Germany). Take note of the IP Address as we continue to setting up VPN. Also, if you go to a random website, since my region is based in germany, I will see german language website.

 ![Annotation 2024-07-06 230143](https://github.com/erik-salgado/VPN-Setup/assets/173113320/e2d79bd0-fee0-4d2f-9858-15f3f545dc14)
 ![Annotation 2024-07-06 230017](https://github.com/erik-salgado/VPN-Setup/assets/173113320/4cf01445-977c-4417-bfd6-64f2f3b6a4b5)

- Install ProtonVPN according to your Operating System. Observations: If you don't have an existing account, sign up for one. I will install the Windows Version.

![Annotation 2024-07-06 230310](https://github.com/erik-salgado/VPN-Setup/assets/173113320/722356b1-9e26-4923-baae-d39d5fb7e1da)
![Annotation 2024-07-06 230459](https://github.com/erik-salgado/VPN-Setup/assets/173113320/fce69adb-b7c0-40f4-857b-f1d808115e86)
![Annotation 2024-07-06 230543](https://github.com/erik-salgado/VPN-Setup/assets/173113320/60c1ab91-0415-4b66-9716-ec08132f8af2)
![Annotation 2024-07-06 230801](https://github.com/erik-salgado/VPN-Setup/assets/173113320/ad87673a-2124-4b3f-8364-9122d156a5f7)

- Log in to ProtonVPN.

![Annotation 2024-07-06 230943](https://github.com/erik-salgado/VPN-Setup/assets/173113320/c6077764-a742-4d57-975b-2f32264ab808)

- Select VPN Server.

![Annotation 2024-07-06 231102](https://github.com/erik-salgado/VPN-Setup/assets/173113320/0936ff2e-c0f6-40ac-b666-4a01c6e6c602)
![Annotation 2024-07-06 231538](https://github.com/erik-salgado/VPN-Setup/assets/173113320/986b2b2e-2f82-4262-be92-d1026978dcbd)

- Go to www.whatismyipaddress.com using your new vpn server. Observations: Our IP Address will now be different as a result of setting up our VPN.  I chosed the Nederlands. Since my location has been changed, I will start seeing content from that exact location in random websites.

![Annotation 2024-07-06 231722](https://github.com/erik-salgado/VPN-Setup/assets/173113320/1bc0a564-5f9d-4590-bd4a-b24c52901592)
![Annotation 2024-07-06 232036](https://github.com/erik-salgado/VPN-Setup/assets/173113320/142d36fb-070b-47c8-8b89-148c30212375)
![Annotation 2024-07-06 231905](https://github.com/erik-salgado/VPN-Setup/assets/173113320/95460cf9-6291-4daf-8573-46f29367b948)

That brings the conclusion for this Lab. Thanks for watching! :)































