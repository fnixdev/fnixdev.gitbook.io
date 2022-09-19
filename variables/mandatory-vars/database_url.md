# DATABASE\_URL

DATABASE\_URL

* First, Go to [cloud.mongodb.com](https://cloud.mongodb.com/) then Sign Up there.
* Login or Sign up, if you don’t have an Account!
* After Login, You’ll be on your Clusters Page

![Clusters](https://telegra.ph/file/46e58355fe5bf648c8108.jpg)

* Choose an option **Build a Cluster** (as the shown picture below)
* Now, You’ll see Pricing Plan section.

![Pricing Plans](https://telegra.ph/file/714afabd905531eedc275.jpg)

* Here, we’re going to use free plan for our userbot.
* After that, you have to select Region and Server, where your Database server will host.

![Create Cluster page](https://telegra.ph/file/69b46491ca2143438bc19.jpg)

```
Tips: Select the Nearest server from your location so it won't take long time to connect
```

* At last, Click on **Create Cluster**.

![Clusters page](https://telegra.ph/file/268f44ba7e1c25f77b1ec.jpg)

```
You have to wait for some time at this Page while your Database is being created. 
```

* After Created, Click on **Network Access** (Can see this option under Security section of Above Image)
* You will see an option **Add IP Address**. Click on that. ![IP Address page](https://telegra.ph/file/8229e06fc38c87e8880ff.jpg)
* Now, **Allow Access From Anywhere**. Then **Confirm**.

![Whitelist IP Address page](https://telegra.ph/file/83c30132c4fc2b639f669.jpg)

```
 Wait until the Status changes from Pending to Active. 
```

* Go Back to **Cluster** option and Click on **Connect**.
* Now. Fill any random **Username** and **Password**

```
Note: Don't use Special character in your password like @#$% etc. 
```

* After filled, Click on **Create MongoDB User**.
* There you are, Select **Choose a connection method**
* Choose **Connect Your Application**
* Now, Select **DRIVER** as `Python` and **VERSION** as `3.6 or later` then Copy the Database link Shown below

```
mongodb+srv://<username>:<password>@mongos0.example.com/myFirstDatabase?retryWrites=true&w=majority
```

* Replace `<password>` with your given Password and `myFirstDatabase` with “`test`” or “`cluster0`” and remove `<>` symbols.

**That’s it**. You have got your **DATABASE\_URL** Var value.
