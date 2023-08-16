<h1>Implementing SSO </h1>
<h2>Description</h2>
In this project, I've set up a dedicated space to explore the capabilities of AWS SSO thoroughly. From streamlined access to seamless integration with AWS services, I'm delving into every facet to ensure a robust understanding of its potential.. Source : https://learn.cantrill.io/

<h2>Languages and Utilities Used</h2>

- <b>Python</b> 


<h2>Environments Used </h2>

- <b>AWS</b> 

<h2>Project walk-through:</h2>

 <h3> Some definitions <h3/>
   
 - Manage SSO Acces - AWS Accounts and External Applications 
 - Flexible Identity Store
 - AWS SSO - Built in Identity Store 
 - AWS Managed Microsof AD 
 - On-premises Microsoft AD (Two way Trust r AD Connector)
 - External Identity Provider - SAML2.0
 - Preferred by AWS vs traditional 'workforce identity federation

   
   <img src="https://i.imgur.com/BQV7dHH.png" height="80%" width="80%" alt="Building and Securing an AWS VPC Steps"/>


<h3>  Implementing SSO: Project baselines <h3/> 
 
    <img src="https://i.imgur.com/mQvSeYf.png" height="80%" width="80%" alt="Building and Securing an AWS VPC Steps"/>

- Permissions set type
<img src="https://i.imgur.com/9VKV0Am.png" height="80%" width="80%" alt="Building and Securing an AWS VPC Steps"/>

- Add user to a Billing Group, then copy the user portal URL

<img src="https://i.imgur.com/tH57e57.png" height="80%" width="80%" alt="Building and Securing an AWS VPC Steps"/>

- Assign this new Billing Group to AWS accounts
  
<img src="https://i.imgur.com/g309kIX.png" height="80%" width="80%" alt="Building and Securing an AWS VPC Steps"/>
<img src="https://i.imgur.com/X9cmuMc.png" height="80%" width="80%" alt="Building and Securing an AWS VPC Steps"/>
<img src="https://i.imgur.com/EjPtZ5p.png" height="80%" width="80%" alt="Building and Securing an AWS VPC Steps"/>

-Test SSO access 


<img src="https://i.imgur.com/KkkFdPZ.png" height="80%" width="80%" alt="Building and Securing an AWS VPC Steps"/>
<img src="https://i.imgur.com/Kc7FMAK.png" height="80%" width="80%" alt="Building and Securing an AWS VPC Steps"/>
<img src="https://i.imgur.com/gzAWb6R.png" height="80%" width="80%" alt="Building and Securing an AWS VPC Steps"/>
 
