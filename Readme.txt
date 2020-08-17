1. Unzip the file robot-python3-installation.zip and double click to install python-3.7.3-amd64.exe

2. Update environment variables for python,In Search, search for This PC > Right click and select properties > click on Advanced system settings > Click on Environment Variables > Add these values under Path variable C:\Users\yourusername\AppData\Local\Programs\Python\Python37;C:\Users\yourusername\AppData\Local\Programs\Python\Python37\Scripts
Please make sure you replaces text "yourusername" with your username

3. Open Command prompt (windows + r and then type cmd) where unzipped files are present and enter below commands to install python packages

4. pip install pywin32-224-cp37-cp37m-win_amd64.whl

5. pip install Pypubsub-4.0.3-py3-none-any.whl

6. Go to Pygments-2.4.2 directory, and type python setup.py install

7. Type cd .. and execute pip install wxPython-4.0.6-cp37-cp37m-win_amd64.whl

8. pip install robotframework-3.1.2-py2.py3-none-any.whl

9. pip install robotframework_ride-1.7.3.1-py2.py3-none-any.whl

10. Install sshlibrary pip install robotframework-sshlibrary

11. Right click and edit ride.bat, replace j11kumar user with your nokia username save the file.

12. Now click on ride.bat file and it will launch RIDE.