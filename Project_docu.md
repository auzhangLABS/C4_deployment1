Documentation for Deployment1
1. Download files for instructor Github.
2. Upload the files to my GitHub.
3. Login into the instructor Jenkins server.
4. Build with Jenkins using my credentials allowing Jenkins to access my Github repository.
5. Build Now.
6. First Error I get is a Shell Script and an Archive JUnit-formatted test results error (see below)
![image](https://github.com/auzhangLABS/C4_deployment1/assets/138344000/9412401d-e892-42aa-985a-f2d82750e26c)
![image](https://github.com/auzhangLABS/C4_deployment1/assets/138344000/859f13da-7af4-4174-bc43-af24fa87b759)
7. Did a rerun and it ran perfectly

![image](https://github.com/auzhangLABS/C4_deployment1/assets/138344000/95f97ed4-935f-4750-beeb-029fc572ade3)

8. Have an issue with Elastic Beanstalk where my status kept degrading. I resolved this by extracting the files from the zip folder and re zipped it.

   
Here is the diagram below:
![image](https://github.com/auzhangLABS/C4_deployment1/assets/138344000/4d47aa50-0a28-441b-830c-97992deeeb02)
