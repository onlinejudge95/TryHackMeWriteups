Task 1 Deploy your first machine
================================
Deploy the machine using the deploy button.

Please note that this is a basic thing and will not be repeated in the coming writeups.
It is expected that in all the tasks where a machine deployment is required it will already be done before starting off with the task.

![Deployed](https://mywriteups.s3.ap-south-1.amazonaws.com/TryHackMe/Tutorial/01-Deploy.png)

Once you have the IP of the deployed VM with you, start your Kali VM and type in the following command
```bash
$ sudo openvpn --config /path/to/.ovpn/file
```

I have setup an alias for the above command by the name of ```thm```

Once the connection is successful, you can launch a browser and visit the IP address of your deployed VM.

From here you will receive a flag for the same.

![Deployed](https://mywriteups.s3.ap-south-1.amazonaws.com/TryHackMe/Tutorial/02-Connection-Flag.png)

Task 2 Next Steps
=================
NA