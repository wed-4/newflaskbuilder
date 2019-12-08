## Flask App Generator

A script that generates a hello world app in Python's flask with proper directory structure that you can modify to build your app.

### How to use
1. $ python3 create-flask-app.py Login-App
2. cd Login-App
3. python3 app.py
4. open up http://localhost:5000 :)

### Add to path(Optional)
1. cp create-flask-app.py /usr/local/bin/
2. chmod +x /usr/local/bin/create-flask-app.py
3. You should now be able to run create-flask-app.py from any directory :)

### Installation
1. Clone the repo
    - $ git clone https://github.com/kouul/create-flask-app

2. Run the script. Do not forget to remove curly brackets and change foldername to your app's name.
    - $ python3 create-flask-app.py {{foldername}}

3. You're done :)

### Coming features
1. Debug option on (-dB)
2. Include Stylesheet and Script (-Ss)
3. ...