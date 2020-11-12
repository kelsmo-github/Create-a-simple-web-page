# Create a simple web page
## Step 1 create a amazon account  
The first step you need to do in this project is to create an Amazon AWS account.
#### If you don't have an account 
[Click this link](https://portal.aws.amazon.com/billing/signup?redirect_url=https%3A%2F%2Faws.amazon.com%2Fregistration-confirmation#/start) and fill in the infomation as per the guidance on the site. 
#### If you have an account
Follow these steps.
1. [Click this link](https://signin.aws.amazon.com/signin?redirect_uri=https%3A%2F%2Fconsole.aws.amazon.com%2Fconsole%2Fhome%3Fstate%3DhashArgs%2523%26isauthcode%3Dtrue&client_id=arn%3Aaws%3Aiam%3A%3A015428540659%3Auser%2Fhomepage&forceMobileApp=0&code_challenge=JxKVl9bU9sZVyOGch1I5BVWAhLF8pPqtlFnGVrQkJqY&code_challenge_method=SHA-256)
2. Click __Root user.__ 
3. Fill in your account email. 
4. Click __Next__
5. type in your password. 
6. Click __Sign in.__ 
## Step 2 launch an "EC2 Server" instance.
Now we're going to launch a EC2 Server to do this you need to follow these steps.
1. [Click this link](https://us-east-2.console.aws.amazon.com/ec2/v2/home?region=us-east-2#Home:)
2. Scroll down and click __Launch Instance__ 
3. Scroll down a select this option ![alt text](https://user-images.githubusercontent.com/73938892/98261959-55787080-1f85-11eb-8f0c-37733bc50fc0.png "Ubuntu Server 20.04 LTS (HVM), SSD Volume Type")
4. Select the free option and then click __Review and launch__ ![alt text](https://user-images.githubusercontent.com/73938892/98263561-47c3ea80-1f87-11eb-9f97-fea5afd60e19.png "free option")
5. Click __Launch__ ![alt text](https://user-images.githubusercontent.com/73938892/98931925-f95ea080-24de-11eb-9b65-0a5158a35d1e.png "launch")
6. Select __create a new key pair__ make your __key pair name__ ___key pair___ ![alt text](https://user-images.githubusercontent.com/73938892/98933794-6b37e980-24e1-11eb-8129-7b4f1fe07358.png "key pair name")
7. Click __View Instances__ ![alt text](https://user-images.githubusercontent.com/73938892/98934586-a1c23400-24e2-11eb-90f9-199a39e5129e.png "view instances")
## Step 3 get a defult Apache website running
1. Click on your __Instance ID__ ![Screen Shot 2020-11-12 at 3 36 43 pm](https://user-images.githubusercontent.com/73938892/98953588-26ba4700-24fd-11eb-841f-6068b21b4f53.png)
2. Click on __Security__ ![Screen Shot 2020-11-12 at 3 41 34 pm](https://user-images.githubusercontent.com/73938892/98954142-c7106b80-24fd-11eb-87f4-50e898380b39.png)
3. Click on your __Security group__ ![Screen Shot 2020-11-12 at 3 45 27 pm](https://user-images.githubusercontent.com/73938892/98954821-7e0ce700-24fe-11eb-90ea-c8bae145b33d.png)
4. Click on __Add rule__ ![Screen Shot 2020-11-12 at 3 50 12 pm](https://user-images.githubusercontent.com/73938892/98955297-012e3d00-24ff-11eb-800c-845cfa5431c4.png)
5. Clich on __Custom TCP__ and select __HTTP__ and then click on the text box next to custom and select the first option then click __save rules__ ![Screen Shot 2020-11-12 at 3 53 28 pm](https://user-images.githubusercontent.com/73938892/98956108-f0ca9200-24ff-11eb-8915-ea5135f0ad1c.png)
6. __now open Iterm__
