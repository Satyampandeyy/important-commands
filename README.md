# Important details
current aws instance: mishra.apoorv8858@gmail.com
password: 7275774361@Sp

eureka.client.register-with-eureka=true
eureka.client.fetch-registry=true
eureka.client.service-url.defaultZone=http://service-registry.azurewebsites.net/eureka/
eureka.instance.hostname=localhost
checking=working properly!!

GOOGLE
client id:1069395401778-khnfkk3rqg2om6jr3cpt9resl08hbfja.apps.googleusercontent.com
client-secret:J7wtnLBLO8HGqF6d6slJtSxE

FACEBOOK
ID:1332406363796740
Client-secret:8ca334c9662f04b43bef3fd47193d842

RAZORPAY
KEY ID:rzp_test_XJdQgPS9NIRk9W
KeyID SECRET:IRIhuj3JGmfmCcUdQ3EQDcyG

Bundeled seo:
id : satyam123
password: z4d48gxrt

Docker hub id:sheebupaare
Docker hub password: 7275774361Sp

remotefile busy instance password: ggSpf-gLceT2R&NG5bJ52pjE.I6crGmm

create new angular project:
ng new projectname

How to install bootstrap in angular project

1.npm install bootstrap

2.Add this line in styles.css
	@import '~bootstrap/dist/css/bootstrap.min.css';

"serve:prerender": "http-server -c-1 dist/blog/browser",
----------------------------------------------------
How to install angular univesal in project:

1. ng add @nguniversal/express-engine

To resolve local storage not defined
Step 1: Run this command:
npm i localstorage-polyfill --save
Step 2: Add these two lines in server.ts file:
import 'localstorage-polyfill'
global['localStorage'] = localStorage;

How to install server side rendering:
1. As you install angular universal it will run on ssr using command:
 npm run dev:ssr
----------------------------------------------------

Testy Codeiz -Angular 9 Projects| Restaurants App in angular|

bookId:productId

https://stripe.com/docs/payments/accept-a-payment-charges
create a charge with token in spring boot in strip

Reload Page after redirecting
    if (!localStorage.getItem('foo')) { 
      localStorage.setItem('foo', 'no reload') 
      location.reload() 
    } else {
      localStorage.removeItem('foo') 
    }
	
spring.data.mongodb.host=insurancedatabase-shard-00-02.vm7hr.mongodb.net:27017
spring.data.mongodb.uri=mongodb+srv://admin:1234@insurancedatabase.vm7hr.mongodb.net/myFirstDatabase?retryWrites=true&w=majority
spring.data.mongodb.database=InsuranceDatabase
spring.data.mongodb.port=27017
------------------------------------------
gcloud auth configure-docker
gcloud auth login
gcloud config set project facteco-portal

docker tag amazingfact:v2 gcr.io/mythical-plate-341418/amazingfact:v2
docker push gcr.io/mythical-plate-341418/amazingfact:v2

FOR SPRING BOOT APPLICATION
Step 1: do maven build or gradle build based on project type
STEP 2: docker build -t v4 .
STEP 2: docker tag b gcr.io/apinsumiddleware/b
STEP 3: docker push gcr.io/apinsumiddleware/b

docker tag s2 gcr.io/earnest-airline-341507/s2
docker push gcr.io/earnest-airline-341507/s2

apinsu:
docker tag amazingfactangular:z48 gcr.io/apinsumiddleware-341620/amazingfactangular:z48
docker push gcr.io/apinsumiddleware-341620/amazingfactangular:z48

Run docker image -> docker run -p 8080:8080 wt6
amazingfact-0.0.1-SNAPSHOT.jar

Portal:
docker tag amazingfactangular:z48 gcr.io/facteco-portal/amazingfactangular:z48
docker push gcr.io/facteco-portal/amazingfactangular:z48

-------------------

PUSH IN SPRING BOOT

Run angular universal:
npm run dev:ssr 

--------------------------------

ng g c login --module=customer
background-color:rgba(14, 185, 253, 0.5);

------------------------------
for Mongodb connection in spring boot:

1.right click on main class and click run configuration.
2.Go to argument
3.put in virtual machine argument -Djdk.tls.client.protocols=TLSv1.2 
search virtual machine argument in project and run this:
-Djdk.tls.client.protocols=TLSv1.2

---------------------------
how to configure google cloud authentication to push image to gcr
1.gcloud auth login

2.gcloud config set project factmiddleware
--------------------------
PROJECT DETAILS:
Insurance project->surajtiwari7733@gmail.com password:7275774361
Blogging project->surajtiwari7733@gmail.com password:7275774361

--------------------------
How to add custom domain in google:
1.Go to google cloud then go to "Manage custom domain"
2.Go to add Mapping
3.verify domain 
4.Add A record to godaddy by looking into DNS record given while doing add mapping process in step 2.

-----------------------------
How to build maven project
1. Go to project(application.java) run as run confuguration.
2. Then click on goals and put "clean install"

----------------------
How to build gradle project
1. delete build folder in gradle project
2. Go to project build.gradle file(where build.gradle file is present) open in cmd and run command  "gradle w build"

----------------------
How tocreate GCR KeyID
1. Go to service account
2. Manage Keys
3. Add Keys(Json format)
------------------------
<meta name="robots" content="noindex">

ctrl+alt+f->indentations
-----------
(window as any).process = {
    env: { DEBUG: undefined },
  };
  
-------------------------------
To implement ckeditor:
1. search in google "ckeditor for angular"
2.install npm install --save @ckeditor/ckeditor5-angular
3.install npm install --save @ckeditor/ckeditor5-build-classic

-------------------------------------
How to connect with Putty on AWS:
1.Download ppk key
2.When putty open give hostname as what is present in ec2 intance after selecting instance connect option will come there below 
		example (ubuntu@ec2-54-201-253-72.us-west-2.compute.amazonaws.com) so this is hostanme and port give 22 in putty
3. Open putty on left side go to SSH and insidethat click on Auth then browse your ppk key and then click ok.
4.Run these below commond once connected with putty for first time(below are ubuntu server command):

sudo apt-get update

sudo apt-get install \
    apt-transport-https \
    ca-certificates \
    curl \
    gnupg-agent \
    software-properties-common
	
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -

sudo apt-get install docker-ce docker-ce-cli containerd.io

apt-cache madison docker-ce

sudo apt-get install docker-ce docker-ce-cli containerd.io

sudo apt install docker.io

sudo apt install docker-compose

sudo chmod 666 /var/run/docker.sock  (If error occur-> Got permission denied while trying to connect to the Docker daemon )

youtube link: https://www.youtube.com/watch?v=awFLzy0XwXo
 
-------------------------------------------
How to connect on aws with filezilla:
1. Open filezilla client and click on edit and setting then click on SFTP then browse and select your ppk key
2. Pick Host as what is present in ec2 intance after selecting instance connect option will come there below 
		example (ubuntu@ec2-54-201-253-72.us-west-2.compute.amazonaws.com) so this is hostanme and port give 22 in Filezilla
		
---------------------------------------------------------------------------------------------
docker command:
1.docker ps -a (to check docker)
2.docker stop containerid
3.docker run -d -p 8080:8080 imagename (left 8080 is browser, right 8080 is expose port,in my code 8080 is for backened and 4000 for frontend)
4.docker system prune -a

--------------------------------------------
Dockerhub command:
1.docker tag  amazingfactangular:v90 sheebupaare/amazingfactangular:v91
2. docker push sheebupaare/amazingfactangular:v91
3.docker run -d -p 80:4000 sheebupaare/amazingfactangular:version5 (in Putty)

---------------------------------------------
How to connect with AWS S3 Bucket using code:
1. Create s3 bucket go inside bucket and got to permission
2. Below there will be bucket policy click on edit and put below code this will make bucker public:
{
  "Version": "2012-10-17",
  "Statement": [
    {
      "Effect": "Allow",
      "Principal": "*",
      "Action": [
        "*"
      ],
      "Resource": "arn:aws:s3:::factecoimagebucket/*"
    }
  ]
}
---------------------------------------------
How to create awsBucket S3 accesskey and secret access key for AWS:
1. Go to IAM ->then users-> click add users -> enter user name -> then click "Provide user access to the AWS Management Console"
2. Once you select this -> then select "I want to create an IAM users" -> then click next -> then select "Attach policies directly"
3. then under permission policies select "AmazonS3FullAccess"-> then next->then create user -> then go inside that user and click "Security Credentials"
4. Scroll below and go to Access keys section and click on "Create Access key" here you will get your access key and secret.
----------------------------------------------
us-east-1

docker run -d -p 80:8080 sheebupaare/task2:latest
docker run -d -p 80:4000 sheebupaare/facteco:latest
docker build -t version4 .
docker tag version4 sheebupaare/v5:version4
docker push sheebupaare/amazingfactangular:v91
docker pull sheebupaare/facteco:latest
docker pull sheebupaare/facteco:version2
docker run -d -p 80:4000 sheebupaare/facteco:version2
docker pull sheebupaare/version2:latest
docker start c4b983bcd011

docker run -d -p 80:8080 sheebupaare/version2:latest
docker pull sheebupaare/vers3:latestdocker run -p 80:8080 sheebupaare/vers3:latest

docker run -d -p 80:4000 sheebupaare/facteco:latest
docker run -d -p 80:4000 sheebupaare/storefrontend:latest
docker pull sheebupaare/storefrontend:updated
docker pull sheebupaare/storefrontend:latest
--------------------------------------------------
Steps for chat gpt search:
step 1: I am going to write a blog on above topic kindly give me the keywords on which I should work on.

step 2: give me phrases.

step 3: - make outline for the blog about Adipurush movie controversy
		- make outline for the blog about Controversial first-look poster
		- make outline for the blog about Provoking interpretation and potential misrepresentation
		
step 4: write intoduction for me

step 4: sabhi outline banwane k badd iska content copy kr k google translater pe daal do 
step 5: usko google doc pe copy kr lo uske baad "google input tool" crome extension download kr lo aur jo copied content hindi me hai use human language me reprase kr do.
step 6: jo reprased hindi me text hai use again english me change kr do. using google translator.
------------------------------------------------------
SEO:
check palagrism: www.quetext.com
check AI detection: https://contentatscale.ai
SEARCH: Please write content for my new blog which is unique and plagrism free.
----------------------------
image size:852*428 -> 530 *298(proper image size)

https://www.holidify.com/places/darjeeling/best-time-to-visit.html
----------------------------------
How to configure github action:
1. go to github and go to repository settings -> then "Actions" -> then under "Actions permissions" select "Allow all actions and reusable workflows"
	-> then select runners -> and open your aws instance -> then on github click on "New self hosted runner" then follow below steps given there to connect with aws instance.

--------------------------------------
How to get github action variable:

host: ${{ secrets.EC2_HOST }}-> this we will get from ec2 instance console in aws(example: ec2-51-20-52-219.eu-north-1.compute.amazonaws.com)
username: ${{ secrets.EC2_USERNAME }} -> it will be ubuntu
key: ${{ secrets.EC2_PRIVATE_KEY }} -> it will be the ssh key which is key-pair which we generate at the time of instant creation we can change it from ppk to pem using following below step: 
- Start PuTTYgen. For Actions, choose Load, and then navigate to your .ppk file.
- Choose the .ppk file, and then choose Open.
-(Optional) For Key passphrase, enter a passphrase. For Confirm passphrase, re-enter your passphrase.
- Note: Although a passphrase isn't required, it's a best practice to specify one. This is a security measure to protect the private key from unauthorized use. A passphrase makes automation difficult, because users must manually log in to an instance or copy files to an instance.
- From the menu at the top of the PuTTY Key Generator, choose Conversions, Export OpenSSH Key.
- Note: If you didn't enter a passphrase, then you receive a PuTTYgen warning. Choose Yes.
- Name the file and add the .pem extension.
- Choose Save.

----------------------------------------
How to take mongodb backup:
- first download "MongoDB Command Line Database Tools Download" by going to link "https://www.mongodb.com/try/download/database-tools"
- set environment variable on your laptop "C:\Program Files\MongoDB\Tools\100\bin"
- run mongodb server by going to cmd and run command : mongod(prerequisite- mongodb should be intalled)
- then to take backup run command:
	mongodump mongodump mongodb+srv://admin:1234@cluster0.ms7i1w9.mongodb.net/factsdatabase?retryWrites=true&w=majority
	
- after taking backup "dump" folder will be created
- to restore mongodb backup on cloud run command(first delete the database which neeeds to be restored.) - 
	mongorestore mongodb+srv://admin:1234@cluster0.ms7i1w9.mongodb.net
	
	NOTE: above command is from connection string which we will get from connecting to mongodb atlas and in code and choose till shown above in string from connection string to restore
	(https://www.youtube.com/watch?v=qcGYBsdOc8I&t=254s)
----------------------------------------

