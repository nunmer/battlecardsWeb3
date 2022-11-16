Online Multiplayer Web3 NFT Card Game

Fixed errors: 
1) Metamask 'eth_accounts' unexpectedly updated accounts 
  Infinite error that crashes browser and loads CPU and Memory
  ![unknown (1)](https://user-images.githubusercontent.com/45449130/200332604-34038474-00ce-45f2-af8b-d3e6f41286e6.png)
![image](https://user-images.githubusercontent.com/45449130/200332623-56976016-895d-4ea0-a019-b9902873fce3.png)


FIX: ![Снимок](https://user-images.githubusercontent.com/45449130/200332946-d897439e-487b-4233-9f60-a8aa60dec879.PNG)
Last lines prevent conflict



2) Build error
  Project builds in local machine perfectly, but vercel build fails. Reason of this is that Windows is not case sensetive as machine that vercel runs.
  Therefore, some errors could not be shown in Windows local machine. In this case:
  ![1ц](https://user-images.githubusercontent.com/45449130/200333621-37269eab-7348-4dfb-9e79-ecceba322ea9.PNG)
  Original code line was: from '../utils/onboard.js', however file name was Onboard.js


3) StarWars theme
  ![image](https://user-images.githubusercontent.com/45449130/202151465-5feb0420-6ae3-4bfd-b024-f7f8df41aa89.png)
