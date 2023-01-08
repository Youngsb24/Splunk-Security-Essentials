# Splunk-Security-Essentials
This Project is a walk through of simple Vulnerability Detection and Windows Patch status using Splunk Security Essentials. Most of what we will be seeing is  detection, but mostly understanding how to prevent from certain malicious activity.We will be dealing with endpoint data majority of this project. Lastly we will understand the reason to keep your system up to date and patch.

# Enviroment Used
Splunk
<br></br>
Splunk app for SSE (splunk security essentials)


<h1>Step 1</h1>
We must first download the Splunk Security Essentials app using the splunkbase.splunk.com
<br>
<img src="https://imgur.com/HOr51Lh.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
</br>

Once you have installed the application, its time to login into your splunk instance and upload it to the instance. Click on "Apps" then hover to "Manage Apps", after clicking manage apps this should display, once you are in apps GUI click "install app from file"

<br>
<img src="https://imgur.com/IX1N75X.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
</br>


<h2>Step 2</h2>
Once the app has been installed , we shall locate the SSE app and click on it. Before we proceed with this project it's important to note what the SSE is used for. SSE is used for exploring use cases and discovering security content to start addressing threats and challenges one may face in their enviroment.We wont go much into detail but i want to show you the basic understanding of SSE and how you can improve your analysis and threat hunting skills utilizing this app, especially if you are interested in the cybersecurity part of splunk or using any other SIEM. 
<br></br>
This is the default screen for the app. As you can see there is a guide to help you with maneuvering through the app. I just want to display some use cases i thought was interesting. Hover over to "content" and select "Security Content" , this shall take you to a page of many use cases (try to explore each use cases when you are free ). 


<br>
<img src="https://imgur.com/8qQ0h1x.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
</br>

<h3>step 3</h3>
exploring Multiple Account Passwords changed by an Admin. As you can see the screen this use case provides us with a lot of details such as the security impact , tactis of the adversary , technique of the adversary and the kill chain step which allowed this malicous activity to be successful. And below SSE will provide a SPL syntax to detect or prevent the malicious activity from spreading.

<br>
<img src="https://imgur.com/1f2Yzgf.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
</br>
