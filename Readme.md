# python amazon reviews scraper
Before you can begin using this tool, you must first set up a few prerequisites. To install all of the Python packages and modules provided in your requirements file, use the `pip install -r requirements.txt` command.

### Get Proxy
>We will need to obtain some proxies since Amazon will ban your IP address if you repeatedly submit requests like a robot.

>If you're looking for a free alternative, you might browse online for Soax. There are many of them, but only a small number of them genuinely work.

>So I'll be using a free proxy from webshare.io, who offers 10 proxies and 1 GB of bandwidth for no charge!

### Step-1 
>Get your username and password by creating an account on webshare.io.

### Step-2
>All of the IP addresses and corresponding ports that you have been provided should be downloaded (or copied).

### Step 3 
Change the ips in the script to your IPs. 
![](https://i.postimg.cc/3NJ6zr5C/image.png)

### Step 4 
You must use your login and password, so either set it up on your machine as an environment variable or use a variable.

![](https://i.postimg.cc/d35PXDWw/image.png)

### Step 5 
You're nearly there. Just provide the command shown below to execute the script:
```shell
`uvicorn main:app --reload`
```

then utilize the program by going to the local URL.

<br>

**Feedback and Contributions**

Please feel free to report an issues if you have any comments; contributions are welcome.

