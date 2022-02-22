# Introduction to AWS Cloud Practitioner Essentials

Course overview

Welcome to the AWS Cloud Practitioner Essentials course.

During Modules 1–10, you will build your AWS Cloud knowledge by learning about AWS Cloud concepts, AWS services, security, architecture, pricing, and support. 

1. The lessons in each module include videos, supporting information, and links to additional resources that further your understanding of AWS services.
2. The knowledge checks and quizzes are opportunities to review the key concepts that were covered in each module. After answering each question, review the detailed answer explanations and external links to reinforce your understanding of the concepts.

In the final Module 11, you will learn about the structure of the AWS Certified Cloud Practitioner exam. You will also review strategies that help you to increase the probability of passing the exam.

You will then conclude the course with a final 30-question assessment.

Now, get started by continuing on to Module 1: Introduction to Amazon Web Services.

# Module 1: Introduction to Amazon Web Services

## Module 1 introduction

### Learning objectives

In this module, you will learn how to:

* Summarize the benefits of AWS.
* Describe differences between on-demand delivery and cloud deployments.
* Summarize the pay-as-you-go pricing model.

**Video transcript**

>  I'm Blaine Sundrud, AWS Training and Certification. I've been teaching technology for more years than I'm willing to admit. After spending time teaching the newspaper industry, I moved to AWS, where I've taught classes globally on many different disciplines, such as security, cloud architecture, DevOps, big data, AI and ML, and theater history. My momma was a teacher. My daddy was a teacher. My grandpa was a bartender. I was born for this.

> Hi, I'm Morgan Willis, a Senior Cloud Technologist at AWS. I started in the IT world about 10 years ago. And along the way, I decided that I was missing something. I missed the help and teaching aspect of IT that I had in my first job in IT support. So, I went into teaching software development in different areas around the U.S. And then I eventually landed here at AWS, where, as a Cloud Technologist, I get to support others in their cloud journey every day.

> And I'm Rudy Chetty. I come from sunny Cape Town, South Africa, home of biltong, boerewors, and bunny chow. I'm a Solutions Architect, and have been with AWS for over three years. Teaching is my passion. And I can't wait for you to dive into the course, and learn. Thank a lot. and good luck.

> This course is gonna cover all the essential information that you need to understand, to be comfortable discussing AWS, to know why it's beneficial to your business.

> AWS offers a massive range of services for every business, starting with basic elements, like compute, storage, and network security tools, through complex solutions like blockchain, machine learning, or artificial intelligence, and robot development platforms, all the way through very specialized tool sets, like video production management systems, and orbital satellites you can rent by the minute.

> All that, however, is way more than we have time to cover in a foundational class like this one. So let's simplify the conversation by starting with the fundamental cloud compute model.

> Almost all modern computing centers around a basic client-server model. Now I know it can be more complicated than that, so let's take a look at our coffee shop.

> This coffee shop is going to give us some real world metaphors to help you understand why AWS can change the way your IT operates.

> Let's make Morgan the server, the barista. And I am the client, the customer. I make a request. In this case, it is for coffee. Now in the computing world, the request could be anything. It could be rain pattern analysis in South Africa, or the latest x-rays of your knee, or videos of kittens. Whatever is the business, basically a customer makes a request, and with permissions, the server responds to that request. All I want is a caffeinated beverage.

> Morgan represents the server part of the client-server model. In AWS, she would be called an Amazon Elastic Compute Cloud, or EC2, an EC2 instance, a virtual server. So from an architectural point of view, the transaction we did is really simple to explain. I, the user, made a request to Morgan, the server. Morgan validated that the request was legitimate, in this case, did I give her money? Then she returned a response, which in this case, is a berry blaster with extra caramel shots.

> Now in the real world, applications can get more complicated than just a single transaction with a single server. In a business solution that is more mature, it can get beautifully complex.

> To avoid this complexity, we're going to start simple. We will build this discussion out so that it is easy for anyone to understand how these concepts build on each other. So, by the end, those complex concepts, they'll be easy to understand. Let's start with a key concept to AWS, and that is, you only pay for what you use.

> This principle makes sense when you run a coffee shop. Employees are only paid when they're in the store working. If Rudy and Morgan are off the clock, well then they don't get paid. The store owner simply decides how many baristas are needed and then just pays for the hours they work. For example, the coffee shop is about to release a new drink, the Pumpkin Monster Spice. In anticipation of this launch, you could always staff your shop with a dozen baristas all day long, just in case you suddenly get an unexpected rush at some point in the day. Only, let's be honest. For most of your day, you don't have near enough customers to justify paying for all those employees.

> And yet, the is exactly what happens in an on-premises data center. You can't just snap your fingers and triple your capacity. At AWS, you don't pre-pay for anything. And you don't have to worry about capacity constraints.

> When you need instances, or baristas, you just click a button, and you have them. And when you don't need them, another click, and they go away, and you stop paying for them. The same way you don't pay for employees for hours that they're not working.

> So, pay for what you need, becomes the first key value of many for running your business on AWS. And that is really why we're here, to help you understand how AWS is built to help you run your business better.

> We hope you stick around for the entire course, as we dive deeper into these concepts, and help launch you on your journey to being a Cloud Practitioner.

### What is a client-server model?

You just learned more about AWS and how almost all of modern computing uses a basic client-server model. Let’s recap what a client-server model is.
A transaction between a client and a server

<div align="center">
<img src=https://i.imgur.com/62ETgyW.png width=50%>
</div>


In computing, a **client** can be a web browser or desktop application that a person interacts with to make requests to computer servers. A **server** can be services such as Amazon Elastic Compute Cloud (Amazon EC2), a type of virtual server.

For example, suppose that a client makes a request for a news article, the score in an online game, or a funny video. The server evaluates the details of this request and fulfills it by returning the information to the client.

## Cloud computing

**Video transcript**

> Before we get deeper into the pieces and parts of AWS, let's zoom out and get a good working definition of cloud. Cloud computing is the on-demand delivery of IT resources over the internet with pay-as-you-go pricing. Let's break this down. On-demand delivery indicates that AWS has the resources you need, when you need them. You don't need to tell us in advance that you're going to need them. Suddenly you find yourself needing 300 virtual servers. Well, just a few clicks and launch them. Or you need 2000 terabytes of storage. You don't have to tell us in advance, just start using the storage you need, when you need it. Don't need them anymore, just as quickly, you can return them and stop paying immediately. That kind of flexibility is just not possible when you're managing your own data centers.

> The idea of IT resources is actually a big part of the AWS philosophy. We often get asked why AWS has so many products and the answer is really simple: Because businesses need them. If there are IT elements that are common across a number of businesses, then this is not a differentiator.

> Take a MySQL database as an example. If your business runs a MySQL database, does your ability to install the MySQL engine make you a better company than your competitors? Well, probably not that. Do you keep backups in a way that makes you superior to other players in your vertical? Again, doubtful. The data inside your database, now that's critically different. The way you build your tables and manage the structures, absolutely separates you from the competition. But the engine is just the engine. 

> At AWS, we call that the undifferentiated heavy lifting of IT. Tasks that are common, often repetitive and ultimately time-consuming; these are the tasks AWS wants to help you with. So you can focus on what makes you unique. Over the internet, seems simple enough, but it implies that you can access those resources using a secure webpage console or programmatically. 

> No additional contracts or sales calls are needed. With pay-as-you-go pricing, we re-emphasize what we pointed out here in the coffee shop. You don't staff a shop with employees 24 hours a day at the same levels you do during peak hours. In fact, some hours, you might not even staff them at all. So why pay for developer environments, for example, on weekends, if your developers aren't working on the weekends?

### Deployment models for cloud computing


When selecting a cloud strategy, a company must consider factors such as required cloud application components, preferred resource management tools, and any legacy IT infrastructure requirements.

The three cloud computing deployment models are cloud-based, on-premises, and hybrid. 

Select each tab to learn about each category.

**1. cloud-based deployment model**

> **基於雲的部署模式**
>  雲端應用程式完全部署在雲端，且應用程式的所有元件都在雲端上執行。雲端中的應用程式可能在雲端中建立，或從現有基礎架構遷移至雲端，以利用雲端運算的優勢。雲端應用程式可以建置在低層級的基礎架構上，或使用較高層級的服務，以取得核心基礎架構的管理、架構和擴展需求摘要。

Run all parts of the application in the cloud.
Migrate existing applications to the cloud.
Design and build new applications in the cloud.
	
In a cloud-based deployment model, you can migrate existing applications to the cloud, or you can design and build new applications in the cloud. You can build those applications on low-level infrastructure that requires your IT staff to manage them. Alternatively, you can build them using higher-level services that reduce the management, architecting, and scaling requirements of the core infrastructure.
	
For example, a company might create an application consisting of virtual servers, databases, and networking components that are fully based in the cloud.

**2. On-premises deployment**

> **本地部署也稱為私有雲部署**
>  內部部署
> 使用虛擬和資源管理工具在內部部署資源，有時稱為「私有雲端」。內部部署無法提供許多雲端運算的優勢，但有時需要利用其提供專用資源的能力。在大多數情況下，這個部署模型與傳統 IT 基礎架構相同，但會使用應用程式管理和虛擬化技術，以嘗試和增加資源使用率。

* Deploy resources by using virtualization and resource management tools.
* Increase resource utilization by using application management and virtualization technologies.

On-premises deployment is also known as a private cloud deployment. In this model, resources are deployed on premises by using virtualization and resource management tools.

For example, you might have applications that run on technology that is fully kept in your on-premises data center. Though this model is much like legacy IT infrastructure, its incorporation of application management and virtualization technologies helps to increase resource utilization.


**3. hybrid deployment**

> **混合部署**
> 混合部署是在雲端資源和不在雲端中的現有資源之間，連接基礎架構和應用程式的一種方法。最常見的混合部署方法是在雲端和現有的內部部署基礎架構之間，將組織的基礎架構擴展至雲端並加以擴大，同時將雲端資源連接到內部系統。如需 AWS 可如何協助您進行混合部署的詳細資訊，請參閱我們的混合頁面。
> 
>  [使用 AWS 的混合雲端] (https://aws.amazon.com/tw/hybrid/?pg=TOCC)

* Connect cloud-based resources to on-premises infrastructure.
* Integrate cloud-based resources with legacy IT applications.

In a hybrid deployment, cloud-based resources are connected to on-premises infrastructure. You might want to use this approach in a number of situations. For example, you have legacy applications that are better maintained on premises, or government regulations require your business to keep certain records on premises.

For example, suppose that a company wants to use cloud services that can automate batch data processing and analytics. However, the company has several legacy applications that are more suitable on premises and will not be migrated to the cloud. With a hybrid deployment, the company would be able to keep the legacy applications on premises while benefiting from the data and analytics services that run in the cloud.

### Benefits of cloud computing

Consider why a company might choose to take a particular cloud computing approach when addressing business needs.


**1. Trade Upfront expense for variable expense**

> 將前期費用換成可變費用

**Upfront expense(前期費用）**  refers to data centers, physical servers, and other resources that you would need to invest in before using them. **Variable expense（變動費用）** means you only pay for computing resources you consume instead of investing heavily in data centers and servers before you know how you’re going to use them.

By taking a cloud computing approach that offers the benefit of variable expense, companies can implement innovative solutions while saving on costs.

**2. Stop spending money to run and maintain data centers**

Computing in data centers often requires you to spend more money and time managing infrastructure and servers. 

A benefit of cloud computing is the ability to focus less on these tasks and more on your applications and customers.

**3. Stop guessing capacity**

With cloud computing, you don’t have to predict how much infrastructure capacity you will need before deploying an application. 

For example, you can launch Amazon EC2 instances when needed, and pay only for the compute time you use. Instead of paying for unused resources or having to deal with limited capacity, you can access only the capacity that you need. You can also scale in or scale out in response to demand.

**4. Benefit from massive economies of scale**

By using cloud computing, you can achieve a lower variable cost than you can get on your own.

Because usage from hundreds of thousands of customers can aggregate in the cloud, providers, such as AWS, can achieve higher economies of scale. The economy of scale translates into lower pay-as-you-go prices. 


**5. Increase speed and agility(敏捷)**

The flexibility of cloud computing makes it easier for you to develop and deploy applications.


This flexibility provides you with more time to experiment and innovate. When computing in data centers, it may take weeks to obtain new resources that you need. By comparison, cloud computing enables you to access new resources within minutes.

**6. Go global in minutes**

The global footprint of the AWS Cloud enables you to deploy applications to customers around the world quickly, while providing them with low latency. This means that even if you are located in a different part of the world than your customers, customers are able to access your applications with minimal delays. 

Later in this course, you will explore the AWS global infrastructure in greater detail. You will examine some of the services that you can use to deliver content to customers around the world.

### Additional resources

To learn more about the concepts that were explored in Module 1, review these resources.

* [AWS glossary AWS詞彙表](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html)

* [Whitepaper: Overview of Amazon Web Services](https://d0.awsstatic.com/whitepapers/aws-overview.pdf)

* [AWS Fundamentals: Overview](https://aws.amazon.com/getting-started/fundamentals-overview/)

* [What is cloud computing?](https://aws.amazon.com/what-is-cloud-computing/)

* [Types of cloud computing](https://aws.amazon.com/types-of-cloud-computing/)

雲端運算模型
雲端運算有三種主要的模型。每個模型各代表雲端運算堆疊的不同部分。

**1. 基礎架構即服務 (IaaS)**

基礎設施即服務有時會以縮寫 IaaS 表示，此包含基本的雲端 IT 建構區塊，且通常能提供聯網功能、電腦 (可以是虛擬或專屬硬體) 及資料儲存空間的存取。基礎設施即服務可為您提供 IT 資源的最大彈性和最高層級管理控制，且與目前許多 IT 部門和開發人員熟悉的現有 IT 資源極其類似。

**2. 平台即服務 (PaaS)**

平台即服務可為組織免除管理基礎設施的麻煩 (通常是硬體和作業系統)，讓您能專注於應用程式的部署和管理。由於不需擔心執行應用程式時的資源採購、容量規劃、軟體維護、修補，或任何其他無差別的繁重工作，因此能有助於提升工作效率。

**3. 軟體即服務 (SaaS)**

軟體即服務可提供由服務供應商執行及管理的完整產品。大部分情況下，一般所說的軟體即服務是指最終使用者應用程式。有了 SaaS 產品，您將不需煩惱如何維護服務或管理基礎架構，只需思考如何運用該特定軟體即可。最常見的 SaaS 應用程式範例就是網路電子郵件，您可以透過該應用程式收發電子郵件，不需管理電子郵件產品中額外的功能，也不必維護執行電子郵件程式的伺服器和作業系統。


* [Cloud computing with AWS](https://aws.amazon.com/what-is-aws/)

## Module 1 quiz

Test your knowledge of some of the key concepts from this module by answering the questions in this quiz.

After answering each question, review the detailed answer explanations to reinforce your understanding of the concepts.

1. What is cloud computing?

[ ] Backing up files that are stored on desktop and mobile devices to prevent data loss

[ ] Deploying applications connected to on-premises infrastructure

[ ] Running code without needing to manage or provision servers

[ ] On-demand delivery of IT resources and applications through the internet with pay-as-you-go pricing

2. What is another name for on-premises deployment?

[ ] Private cloud deployment

[ ] Cloud-based application

[ ] Hybrid deployment

[ ] AWS Cloud

3. How does the scale of cloud computing help you to save costs?

[ ] You do not have to invest in technology resources before using them.

[ ] The aggregated cloud usage from a large number of customers results in lower pay-as-you-go prices.

[ ] Accessing services on-demand helps to prevent excess or limited capacity.

[ ] You can quickly deploy applications to customers and provide them with low latency.

# Module 2: Compute in the Cloud

## Module 2 introduction

### Learning objectives

In this module, you will learn how to:

* Describe the benefits of Amazon EC2 at a basic level.
* Identify the different Amazon EC2 instance types.
* Differentiate between the various billing options for Amazon EC2.
* Summarize the benefits of Amazon EC2 Auto Scaling.
* Summarize the benefits of Elastic Load Balancing.
* Give an example of the uses for Elastic Load Balancing.
* Summarize the differences between Amazon Simple Notification Service (Amazon SNS) and Amazon Simple Queue Service (Amazon SQS).
* Summarize additional AWS compute options.


**Video transcript**

> In this video, we are going to talk at a high level about a service called Amazon Elastic Compute Cloud or EC2. If you remember from our coffee shop, the employees are a metaphor for the client/server model where a client sends a request to the server; the server does some work, and then sends a response. That example is for the coffee shop. But the same idea applies to other businesses. Your business, whether it be in healthcare, manufacturing, insurance, or delivering video content to millions of users all around the world, are also using this model to deliver products, resources, or data to your end users. And you're going to need servers to power your business and your applications. You need raw compute capacity to host your applications and provide the compute power that your business needs. When you're working with AWS, those servers are virtual. And the service you use to gain access to virtual servers is called EC2. 

> Using EC2 for compute is highly flexible, cost effective, and quick when you compare it to running your own servers on premises in a data center that you own. The time and money it takes to get up and running with on-premises resources is fairly high. When you own your own fleet of physical servers, you first have to do a bunch of research to see what type of servers you want to buy and how many you'll need. Then you purchase that hardware up front. You'll wait for multiple weeks or months for a vendor to deliver those servers to you. You then take them to a data center that you own or rent to install them, rack and stack them, and wire them all up. Then you make sure that they are secure and powered up and then they're ready to be used. Only then can you begin to host your applications on top of these servers. The worst part is, once you buy these servers you are stuck with them whether you use them or not. 

> With EC2, it's much easier to get started. AWS took care of the hard part for you already. AWS already built and secured the data centers. AWS has already bought the servers, racked and stacked them, and they are already online ready to be used. AWS is constantly operating a massive amount of compute capacity. And you can use whatever portion of that capacity when you need it. All you have to do is request the EC2 instances you want and they will launch and boot up, ready to be used within a few minutes. Once you're done, you can easily stop or terminate the EC2 instances. You're not locked in or stuck with servers that you don't need or want. Your usage of EC2 instances can vary greatly over time. And you only pay for what you use. Because with EC2, you only pay for running instances, not stopped or terminated instances. 

> EC2 runs on top of physical host machines managed by AWS using virtualization technology. When you spin up an EC2 instance, you aren't necessarily taking an entire host to yourself. Instead, you are sharing the host with multiple other instances, otherwise known as virtual machines. And a hypervisor running on the host machine is responsible for sharing the underlying physical resources between the virtual machines. This idea of sharing underlying hardware is called multitenancy. The hypervisor is responsible for coordinating this multitenancy and it is managed by AWS. The hypervisor is responsible for isolating the virtual machines from each other as they share resources from the host. This means EC2 instances are secure. Even though they may be sharing resources, one EC2 instance is not aware of any other EC2 instances also on that host. They are secure and separate from each other. 

> Luckily, this is not something you, yourself, need to set up. But it's important to know the idea of multitenancy and have a high level understanding of how this works. EC2 gives you a great deal of flexibility and control. Not only can you spin up new servers or take them offline at will, but you also have the flexibility and control over the configuration of those instances. 

> When you provision an EC2 instance, you can choose the operating system based on either Windows or Linux. You can provision thousands of EC2 instances on demand. With a blend of operating systems and configurations to power your business' different applications. 

> Beyond the OS, you also configure what software you want running on the instance. Whether it's your own internal business applications, simple web apps, or complex web apps, databases or third party software like enterprise software packages, you have complete control over what happens on that instance. EC2 instances are also resizable. You might start with a small instance, realize the application you are running is starting to max out that server, and then you can give that instance more memory and more CPU. Which is what we call vertically scaling an instance. 

> In essence, you can make instances bigger or smaller whenever you need to. You also control the networking aspect of EC2. So what type of requests make it to your server and if they are publicly or privately accessible is something you decide. 

> We will touch more on this later in the course in detail. Virtual machines are not a new thing. But the ease of provisioning EC2 instances allows for programmers and businesses to innovate more quickly. AWS has just made it much, much easier and more cost effective for you to acquire servers through this Compute as a Service model. There's a lot more to learn about EC2. We talked about virtualization and the types of software you can run on an EC2 instance. But there is more you can configure with EC2 as well.

### Amazon Elastic Compute Cloud (Amazon EC2)

[Amazon Elastic Compute Cloud (Amazon EC2)](https://aws.amazon.com/ec2/) provides secure, resizable compute capacity in the cloud as Amazon EC2 instances. 

Imagine you are responsible for the architecture of your company's resources and need to support new websites. With traditional on-premises resources, you have to do the following:

* Spend money upfront to purchase hardware.
* Wait for the servers to be delivered to you.
* Install the servers in your physical data center.
* Make all the necessary configurations.

By comparison, with an Amazon EC2 instance you can use a virtual server to run applications in the AWS Cloud.

* You can provision and launch an Amazon EC2 instance within minutes.
* You can stop using it when you have finished running a workload.
* You pay only for the compute time you use when an instance is running, not when it is stopped or terminated.
* You can save costs by paying only for server capacity that you need or want.

### How Amazon EC2 works

<div align="center">
<img src=https://i.imgur.com/lqN1YQx.png width=65%>
</div>

**1. Launch**

First, you launch an instance. Begin by selecting a template with basic configurations for your instance.These configurations include the operating system,application server,or applications. You also select the instance type, whitch is the specific hardware confuration of your instance.

As you are preparing to launch an instance, you specify security settings to control the network traffic that can flow into and out of your instance. Later in this course, we will explore Amazon EC2 security features in greater details.

**2. Connect**

Next, connect to the instance. You can connect to the instance in serveral ways.Your programs and applications have multiple different methods to connect directly to the instance and exchange data. Users can also connect to the instance by logging in and accessing the computer desktop.

**3. Use**

After you have connected to the instance,you can begin using it.You can run commands to install software,add storage,copy and organize files,and more.


### Amazon EC2 instance types

**Video transcript**

> Now that we've learned about EC2 instances and the crucial role they play in AWS, let's talk about the different types of EC2 instances that are available. Thinking back to our coffee shop analogy, you'll remember that EC2 instances are like our employees and that they serve client requests. If we want to have a cafe that can serve a lot of customers, then we're probably going to need multiple employees, right? And they all can't just be cashiers. We also need someone to make the drinks, someone to handle the food, and maybe someone to do that cool latte art that our customers love so much. Like any business, there are a variety of tasks that need to be done, and they often require different skillsets. 

> If we want our business to operate as efficiently as possible, it's important to make sure that an employee's skillset suits their role. In the same way that our coffee shop has different kinds of employees, AWS has different types of EC2 instances that you can spin up and deploy into your AWS environment. 

> Each instance type is grouped under an instance family and are optimized for certain types of tasks. Instance types offer varying combinations of CPU, memory, storage, and networking capacity, and give you the flexibility to choose the appropriate mix of resources for your applications. The different instance families in EC2 are general purpose, compute optimized, memory optimized, accelerated computing, and storage optimized. 

> General purpose instances provide a good balance of compute, memory, and networking resources, and can be used for a variety of diverse workloads like web service or code repositories. 

> Compute optimized instances are ideal for compute-intensive tasks like gaming servers, high performance computing or HPC, and even scientific modeling. 

> Similarly, memory optimized instances are good for memory-intensive tasks. Accelerated computing are good for floating point number calculations, graphics processing, or data pattern matching, as they use hardware accelerators. 

> And finally, storage optimized are good for, can you guess it? Workloads that require high performance for locally stored data. 

> Now, if we map this back to our coffee shop, our cashier becomes a memory optimized EC2 instance, baristas become compute optimized instances, and our latte art employee is an accelerated computing instance type. And there you have it, EC2 instance types.

## Amazon EC2 instance types

[Amazon EC2 instance types](https://aws.amazon.com/ec2/instance-types/) are optimized for different tasks. When selecting an instance type, consider the specific needs of your workloads and applications. This might include requirements for compute, memory, or storage capabilities.

> **1. 一般用途**
> 一般用途的執行個體可平衡運算、記憶體與網路資源，也可用於各種工作負載。這些執行個體非常適合以相同比例使用這些資源的應用程式，如 Web 伺服器和程式碼儲存庫。 
> 
> **2. 運算優化**
> 運算優化執行個體非常適合運算密集型應用程式，這些應用程式受惠於高效能處理器。此系列的執行個體極其適合批次處理工作負載、媒體轉碼、高效能 Web 伺服器、高效能運算 (HPC)、科學建模、專用遊戲伺服器與服務引擎、機器學習推論，以及其他運算密集型應用。
> 
> **3.  記憶體優化**
> 記憶體優化執行個體的設計目的，在於為記憶體內處理大型資料集的工作負載提供快速效能。

> **4. 加速運算**
> 加速運算執行個體使用硬體加速器或協同處理器執行函數 (例如，浮點數計算、圖形處理或資料模式比對)，這比在 CPU 上執行的軟體更有效率。

> **5. 儲存優化**
> 儲存優化執行個體專為需要對本機儲存上的超大型資料集進行高序列讀取及寫入存取的工作量所設計。這些執行個體經過優化，能為應用程式提供每秒數萬次低延遲隨機的 I/O 操作 (IOPS)。
> 
> **6.  執行個體功能**
> 高載效能執行個體
> Amazon EC2 可讓您選擇固定效能執行個體 (例如 M5、C5 和 R5) 和高載效能執行個體 (例如 T3)。高載效能執行個體可提供 CPU 基準效能，並有超越該基準效能的能力。
> 
> **7. 測量執行個體效能**
> 
>  為什麼您應該測量執行個體效能？
> Amazon EC2 可讓您佈建多種執行個體類型，提供不同的 CPU、記憶體、磁碟和聯網組合。您可以輕鬆啟動新執行個體並同時執行測試，我們也建議您測量應用程式的效能，以識別適當的執行個體類型和驗證應用程式架構。我們也建議您進行嚴格的負載/擴展測試，確保您的應用程式可以如預期進行擴展。

**1. General purpose instances（一般用途）**

General purpose instances provide a balance of compute, memory, and networking resources. You can use them for a variety of workloads, such as:

* application servers
* gaming servers
* backend servers for enterprise applications
* small and medium databases

Suppose that you have an application in which the resource needs for compute, memory, and networking are roughly equivalent. You might consider running it on a general purpose instance because the application does not require optimization in any single resource area.

**2. Compute optimized instances（運算優化）**

Compute optimized instances are ideal for compute-bound applications that benefit from high-performance processors. Like general purpose instances, you can use compute optimized instances for workloads such as web, application, and gaming servers.


However, the difference is compute optimized applications are ideal for high-performance web servers, compute-intensive applications servers, and dedicated gaming servers. You can also use compute optimized instances for batch processing workloads that require processing many transactions in a single group.

**3. Memory optimized instances（記憶體優化）**

Memory optimized instances are designed to deliver fast performance for workloads that process large datasets in memory. In computing, memory is a temporary storage area. It holds all the data and instructions that a central processing unit (CPU) needs to be able to complete actions. Before a computer program or application is able to run, it is loaded from storage into memory. This preloading process gives the CPU direct access to the computer program.


Suppose that you have a workload that requires large amounts of data to be preloaded before running an application. This scenario might be a high-performance database or a workload that involves performing real-time processing of a large amount of unstructured data. In these types of use cases, consider using a memory optimized instance. Memory optimized instances enable you to run workloads with high memory needs and receive great performance.

**4. Accelerated computing instances(加速運算)**

Accelerated computing instances use hardware accelerators, or coprocessors, to perform some functions more efficiently than is possible in software running on CPUs. Examples of these functions include floating-point number calculations, graphics processing, and data pattern matching.

In computing, a hardware accelerator is a component that can expedite data processing. Accelerated computing instances are ideal for workloads such as graphics applications, game streaming, and application streaming.

### Knowledge check

Match each description to an Amazon EC2 instance type.

* Ideal for high-performance databases [Memory optimized]

* Suitable for data warehousing applications[Storage optimized]

* Balances compute, memory, and networking resources[General purpose]

* Offers high-performance processors[Compute optimized]

## Amazon EC2 pricing

**Video transcript**

> We talked about EC2 instance types, but you're all probably wondering how much is this gonna cost me? Well, don't fret. For EC2, we have multiple billing options available. 


> The first one and the one that most people are familiar with is called On-Demand. What that means is that you only pay for the duration that your instance runs for. This can be per hour or per second, depending on the instance type and operating system you choose to run. Plus, no long-term commitments or upfront payments are needed. This type of pricing is usually for when you get started and want to spin up servers to test out workloads and play around. You don't need any prior contracts or communication with AWS to use On-Demand pricing. You can also use them to get a baseline for your average usage, which leads us to our next pricing option, Savings Plan. 


> Savings Plan offers low prices on EC2 usage in exchange for a commitment to a consistent amount of usage measured in dollars per hour for a one or three-year term. This flexible pricing model can therefore provide savings of up to 72% on your AWS compute usage. This can lower prices on your EC2 usage, regardless of instance family, size, OS, tenancy, or AWS region. This also applies to AWS Fargate and AWS Lambda usage, which are serverless compute options that we will cover later in this course. 


> Another option is Reserved Instances. These are suited for steady-state workloads or ones with predictable usage and offer you up to a 75% discount versus On-Demand pricing. You qualify for a discount once you commit to a one or three-year term and can pay for them with three payment options: all upfront, where you pay for them in full when you commit; partial upfront, where you pay for a portion when you commit; and no upfront, where you don't pay anything at the beginning. 


> The next option is Spot Instances, and they allow you to request spare Amazon EC2 computing capacity for up to 90% off of the On-Demand price. The catch here is that AWS can reclaim the instance at any time they need it, giving you a two-minute warning to finish up work and save state. You can always resume later if needed. So when choosing Spot Instances, make sure your workloads can tolerate being interrupted. A good example of those are batch workloads. 


> And finally, we have Dedicated Hosts, which are physical hosts dedicated for your use for EC2. These are usually for meeting certain compliance requirements and nobody else will share tenancy of that host.

### Amazon EC2 pricing

With Amazon EC2, you pay only for the compute time that you use. Amazon EC2 offers a variety of pricing options for different use cases. For example, if your use case can withstand interruptions, you can save with Spot Instances. You can also save by committing early and locking in a minimum level of use with Reserved Instances.

**On-Demand Instances(經請求)**

On-Demand Instances are ideal for short-term, irregular workloads that cannot be interrupted. No upfront costs or minimum contracts apply. The instances run continuously until you stop them, and you pay for only the compute time you use.

Sample use cases for On-Demand Instances include developing and testing applications and running applications that have unpredictable usage patterns. On-Demand Instances are not recommended for workloads that last a year or longer because these workloads can experience greater cost savings using Reserved Instances.

**Amazon EC2 Savings Plans**

AWS offers Savings Plans for several compute services, including Amazon EC2. Amazon EC2 Savings Plans enable you to reduce your compute costs by committing to a consistent amount of compute usage for a **1-year** or **3-year** term. This term commitment results in savings of up to 66% over On-Demand costs.

Any usage up to the commitment is charged at the discounted plan rate (for example, $10 an hour). Any usage beyond the commitment is charged at regular On-Demand rates.

Later in this course, you will review AWS Cost Explorer, a tool that enables you to visualize, understand, and manage your AWS costs and usage over time. If you are considering your options for Savings Plans, AWS Cost Explorer can analyze your Amazon EC2 usage over the past 7, 30, or 60 days. AWS Cost Explorer also provides customized recommendations for Savings Plans. These recommendations estimate how much you could save on your monthly Amazon EC2 costs, based on previous Amazon EC2 usage and the hourly commitment amount in a 1-year or 3-year plan.

**Reserved Instances（預留實例）** 

Reserved Instances are a billing discount applied to the use of On-Demand Instances in your account. You can purchase Standard Reserved and Convertible Reserved Instances for a 1-year or 3-year term, and Scheduled Reserved Instances for a 1-year term. You realize greater cost savings with the 3-year option.


At the end of a Reserved Instance term, you can continue using the Amazon EC2 instance without interruption. However, you are charged On-Demand rates until you do one of the following:

* Terminate the instance.
* Purchase a new Reserved Instance that matches the instance attributes (instance type, Region, tenancy, and platform).

**Spot Instances**

Spot Instances are ideal for workloads with flexible start and end times, or that can withstand interruptions. Spot Instances use unused Amazon EC2 computing capacity and offer you cost savings at up to 90% off of On-Demand prices.

Suppose that you have a background processing job that can start and stop as needed (such as the data processing job for a customer survey). You want to start and stop the processing job without affecting the overall operations of your business. If you make a Spot request and Amazon EC2 capacity is available, your Spot Instance launches. However, if you make a Spot request and Amazon EC2 capacity is unavailable, the request is not successful until capacity becomes available. The unavailable capacity might delay the launch of your background processing job.

After you have launched a Spot Instance, if capacity is no longer available or demand for Spot Instances increases, your instance may be interrupted. This might not pose any issues for your background processing job. However, in the earlier example of developing and testing applications, you would most likely want to avoid unexpected interruptions. Therefore, choose a different EC2 instance type that is ideal for those tasks.

**Dedicated Hosts（專用主機）**

Dedicated Hosts are physical servers with Amazon EC2 instance capacity that is fully dedicated to your use. 

You can use your existing per-socket, per-core, or per-VM software licenses to help maintain license compliance. You can purchase On-Demand Dedicated Hosts and Dedicated Hosts Reservations. Of all the Amazon EC2 options that were covered, Dedicated Hosts are the most expensive.

### Knowledge check

What is the difference between Amazon EC2 Savings Plans and Spot Instances?

**1. Saving Plans**

ideal for workloads that involve a consistent amount of compute usage over a **1-year** or **3-year** term.

you can reduce your compute cost by up to **72%** over on-demand cost.

**2. Spot instances（現貨實例）**

> Spot 實例非常適合具有靈活開始和結束時間或可以承受中斷的工作負載。

ideal for workloads with flexible start and end time, or that can withstand interrputions. With Spot instance,you can reduce your compute cost by up to 90% over on-demand cost.

Do <font color="red">NOT</font> require contracts or a commitment to a consistent amount of compute usage.

## Scaling Amazon EC2

**Video transcript**

> So we have a good idea now on the basics of EC2 and how it can help with any compute needs, like making coffee. Well, like metaphorically making coffee. The coffee represents the, whatever your instance is producing. The next thing we want to talk about is another major benefit of AWS, scalability and elasticity, or how capacity can grow and shrink, based on business needs.

> Here is the on-prem data center dilemma. If your business is like 99% of all businesses out in the world, your customer workloads vary over time: perhaps over a simple 24 hour period, or you might have seasons where you're busy, and weeks that are not in demand. If you're building out a data center, the question is, what is the right amount of hardware to purchase? If you buy for the average amount, the average usage, you won't be wasting money on average. But when the peak loads come in, you won't have the hardware to service the customers, especially during the critical moments to expect to be making all your results.


> Now, if you buy for the top max load, you might have happy customers, but for most of the year, you'll have idle resources. Which means your average utilization is very low. And I've seen data centers with average utilization under 10%, just out of fear of missing peak demand. So how do you solve the problem on-premises? Well the truth is, you can't. And here's where AWS changes the conversation entirely. 


> What if you could provision your workload to exactly the demand, every hour, every day? Well, now you have happy customers, because they can always get the services they want. And you have a happy financial officer because they get the ROI your company needs. 


> And here's how it works. Morgan is behind the counter. She's taking orders and we have a decoupled system. Morgan isn't doing all of the work here, so we need somebody making the drinks. It looks like Rudy's up. Now, the first problem I wanna solve, is the idea that we plan for a disaster. There's a great quote by Werner Vogels that says, "Everything fails all the time, so plan for failure and nothing fails." Or in other words, we ask ourselves what would happen if we lost our order taking instance? Well, we'd be out of business until we'd get another person to work the line, sorry, another instance up and running. 


> So here is where AWS makes it really simple. Using the same programmatic method we used to create the original Morgan, we can create a second Morgan. So if one fails, we have another one already on the front line and taking orders. The customers never lose service. Well, don't forget about the backend. Let's make our processing instances redundant as well. So that gets our regular operating capacity. We now have a highly available system, with no single point of failure. And as long as the number of customers in line stays the same, we're good. But you know that's gonna change, right? So let's take a look at what's going to happen when we have a rush of customers, an increase in demand.

### Scalability

Scalability involves beginning with only the resources you need and designing your architecture to automatically respond to changing demand by scaling out or in. As a result, you pay for only the resources you use. You don’t have to worry about a lack of computing capacity to meet your customers’ needs.

If you wanted the scaling process to happen automatically, which AWS service would you use? The AWS service that provides this functionality for Amazon EC2 instances is Amazon EC2 Auto Scaling.

### Amazon EC2 Auto Scaling

If you’ve tried to access a website that wouldn’t load and frequently timed out, the website might have received more requests than it was able to handle. This situation is similar to waiting in a long line at a coffee shop, when there is only one barista present to take orders from customers.
Bar graph depicting demand and unused capacity over a 7-day period.

<div align="center">
<img src=https://i.imgur.com/KmbON8q.png width=50%>
</div>


Amazon EC2 Auto Scaling enables you to automatically add or remove Amazon EC2 instances in response to changing application demand. By automatically scaling your instances in and out as needed, you are able to maintain a greater sense of application availability.

Within Amazon EC2 Auto Scaling, you can use two approaches: dynamic scaling and predictive scaling.

* Dynamic scaling responds to changing demand. 
* Predictive scaling automatically schedules the right number of Amazon EC2 instances based on predicted demand.

> To scale faster, you can use dynamic scaling and predictive scaling together.

**Video transcript**

> Now there are two ways to handle growing demands. You can scale up, or scale out. Scaling up means adding more power to the machines that are running, which might make sense in a few cases but think about it. When you have an increase in customers, a bigger instance of Morgan really can't take a customer's order any faster. Because that depends on the customer more than Morgan.

> "I'll take an espresso. Oh, wait, is that organic? Make it a soy latte? Actually, I don't know. Do you just have tea?"

> What we need are, well, more Morgans. Customers? Oh, no! Looks like the processing instances are about to get overloaded. So let's scale them as well.

> Obvious question is obvious. How come they are more order taking instances than order makers?

> Well, in this case, the amount of work you can get done is still more than the order machines can send your way. You don't have a backlog. So no reason to add more worker instances. This is one of the great things about decoupling the system. You can end up with exactly the right amount of power for each part of your process, rather than over provisioning to solve a separate problem. Okay, looks like we just cleared that rush.


> Now here is where AWS really makes a difference to your business. All these extra workers that are sitting around idle, if you don't need them, send them home or stop the instances. Amazon EC2 Auto Scaling. Adds instances based on demand and then decommissions instances when they are no longer needed. This means that every minute of the day, you always have the correct number of instances. Happy customers. Happy CFO. Happy architecture.


### Example: Amazon EC2 Auto Scaling

In the cloud, computing power is a programmatic resource, so you can take a more flexible approach to the issue of scaling. By adding Amazon EC2 Auto Scaling to an application, you can add new instances to the application when necessary and terminate them when no longer needed.

Suppose that you are preparing to launch an application on Amazon EC2 instances. When configuring the size of your Auto Scaling group, you might set the minimum number of Amazon EC2 instances at one. This means that at all times, there must be at least one Amazon EC2 instance running.

<div align="center">
<img src=https://i.imgur.com/dQVSxoU.png width=60%>
</div>


Diagram of an Amazon EC2 instances scaling in and out as part of an Auto Scaling group

When you create an Auto Scaling group, you can set the minimum number of Amazon EC2 instances. The minimum capacity is the number of Amazon EC2 instances that launch immediately after you have created the Auto Scaling group. In this example, the Auto Scaling group has a minimum capacity of one Amazon EC2 instance.


Next, you can set the **desired capacity（所需容量）** at two Amazon EC2 instances even though your application needs a minimum of a single Amazon EC2 instance to run.

> If you do not specify the desired number of Amazon EC2 instances in an Auto Scaling group, the desired capacity defaults to your minimum capacity.
> 如果您未在 Auto Scaling 組中指定所需的 Amazon EC2 實例數，則所需容量默認為您的最小容量。

The third configuration that you can set in an Auto Scaling group is the maximum capacity. For example, you might configure the Auto Scaling group to scale out in response to increased demand, but only to a maximum of four Amazon EC2 instances.

Because Amazon EC2 Auto Scaling uses Amazon EC2 instances, you pay for only the instances you use, when you use them. You now have a cost-effective architecture that provides the best customer experience while reducing expenses.


## Directing traffic with Elastic Load Balancing

**Video transcript**

> So we solved the scaling problem with Amazon EC2 Auto Scaling. But now we've got a bit of a traffic problem, don't we? Let's take a look at the situation. When customers come into the coffee shop, right now they have three options for which cashier to talk to to place an order. And oddly enough, most of them are lining up in one line, causing an uneven distribution of customers per line. Even though we have other cashiers waiting to take orders, standing around doing nothing. Customers come in and aren't sure exactly where to route their order. It would help a lot if we added a host to the situation. 

> A host stands at the door and when customers come into the coffee shop, they tell them which line to proceed to for placing their order. The host keeps an eye on the cashier's taking orders, and counts the number of people in line each cashier is serving. Then it will direct new customers to the cashier that has the shortest line, that's the least bogged down, thus allowing the lines to be even across cashiers and helping customers be served in the most efficient manner possible. 

> The same idea applies to your AWS environment. When you have multiple EC2 instances all running the same program, to serve the same purpose, and a request comes in, how does that request know which EC2 instance to go to? How can you ensure there's an even distribution of workload across EC2 instances? So not just one is backed up while the others are idle sitting by. You need a way to route requests to instances to process that request. What you need to solve this is called load balancing. 

> A load balancer is an application that takes in requests and routes them to the instances to be processed. Now, there are many off the shelf load balancers that work great on AWS. And if you have a favorite flavor that already does exactly what you want, then feel free to keep using it. In which case it will be up to your operations team to install, manage, update, scale, handle fail over, and availability. It's doable. Odds are what you really need is just to properly distribute traffic in a high performance, cost-efficient, highly available, automatically scalable system that you can just set and forget. 

> Introducing Elastic Load Balancing. Elastic Load Balancing, or ELB, is one of the first major managed services we're going to talk about in this course. And it's engineered to address the undifferentiated heavy lifting of load balancing. To illustrate this point, I need to zoom out a bit here. To begin with, Elastic Load Balancing is a regional construct, and we'll explain more of what that means in later videos. But the key value for you is that because it runs at the Region level rather than on individual EC2 instances, the service is automatically highly available with no additional effort on your part. 

> ELB is automatically scalable. As your traffic grows, ELB is designed to handle the additional throughput with no change to the hourly cost. When your EC2 fleet auto-scales out, as each instance comes online, the auto-scaling service just lets the Elastic Load Balancing service know that it's ready to handle the traffic, and off it goes. Once the fleet scales in, ELB first stops all new traffic, and waits for the existing requests to complete, to drain out. Once they do that, then the auto-scaling engine can terminate the instances without disruption to existing customers. 

> ELB is not only used for external traffic. Let's look at the ordering tier, and how it communicates with the production tier. Right now, each front end instance is aware of each backend instance. And if a new back end instance comes online, in this current architecture, it would have to tell every front end instance that it can now accept traffic. This is complicated enough with just half a dozen instances. Now imagine you have potentially hundreds of instances on both tiers. Each tier shifting constantly based on demand. Just keeping them networked efficiently is impossible. 

> Well, we solve the back end traffic chaos with an ELB as well. Because ELB is regional, it's a single URL that each front end instance uses. Then the ELB directs traffic to the back end that has the least outstanding requests. Now, if the back end scales, once the new instance is ready, it just tells the ELB that it can take traffic, and it gets to work. The front end doesn't know and doesn't care how many back end instances are running. This is true decoupled architecture.

> There's even more that the ELB can do that we'll learn about later, but this is good enough for now. The key is choosing the right tool for the right job, which is one of the reasons AWS offers so many different services. For example, back end communication. There are many ways to handle it and ELB is just one method. Next, we'll talk about some other services that might work even better for some architectures.


### Elastic Load Balancing（彈性負載平衡）

Elastic Load Balancing is the AWS service that automatically distributes incoming application traffic across multiple resources, such as Amazon EC2 instances. 

A load balancer acts as a single point of contact for all incoming web traffic to your Auto Scaling group. This means that as you add or remove Amazon EC2 instances in response to the amount of incoming traffic, these requests route to the load balancer first. Then, the requests spread across multiple resources that will handle them. For example, if you have multiple Amazon EC2 instances, Elastic Load Balancing distributes the workload across the multiple instances so that no single instance has to carry the bulk of it. 

Although Elastic Load Balancing and Amazon EC2 Auto Scaling are separate services, they work together to help ensure that applications running in Amazon EC2 can provide high performance and availability. 

### Example: Elastic Load Balancing

**Low-demand period（低需求期）**

<div align="center">
<img src=https://i.imgur.com/q1vDFo6.png width=50%>
</div>

Here’s an example of how Elastic Load Balancing works. Suppose that a few customers have come to the coffee shop and are ready to place their orders. 

If only a few registers are open, this matches the demand of customers who need service. The coffee shop is less likely to have open registers with no customers. In this example, you can think of the registers as Amazon EC2 instances.


**High-demand period（高需求期）**

<div align="center">
<img src=https://i.imgur.com/ENXz5N5.png width=50%>
</div>


Throughout the day, as the number of customers increases, the coffee shop opens more registers to accommodate them. In the diagram, the Auto Scaling group represents this.

Additionally, a coffee shop employee directs customers to the most appropriate register so that the number of requests can evenly distribute across the open registers. You can think of this coffee shop employee as a load balancer. 


## Messaging and queuing

**Video transcript**

> Let's talk about messaging and queuing. In the coffee shop, there are cashiers taking orders from the customers and baristas making the orders. Currently, the cashier takes the order, writes it down with a pen and paper, and delivers this order to the barista. The barista then takes the paper and makes the order. When the next order comes in, the process repeats. This works great as long as both the cashier and the barista are in sync. But what would happen if the cashier took the order and turned to pass it to the barista and the barista was out on break or busy with another order? Well, that cashier is stuck until the barista is ready to take the order. And at a certain point, the order will probably be dropped so the cashier can go serve the next customer. 


> You can see how this is a flawed process, because as soon as either the cashier or barista is out of sync, the process will degrade, causing slow downs in receiving orders and failures to complete orders at all. A much better process would be to introduce some sort of buffer or queue into the system. Instead of handing the order directly to the barista, the cashier would post the order to some sort of buffer, like an order board. 


> This idea of placing messages into a buffer is called messaging and queuing. Just as our cashier sends orders to the barista, applications send messages to each other to communicate. If applications communicate directly like our cashier and barista previously, this is called being tightly coupled. 


> A hallmark trait of a tightly coupled architecture is where if a single component fails or changes, it causes issues for other components or even the whole system. For example, if we have Application A and it is sending messages directly to Application B, if Application B has a failure and cannot accept those messages, Application A will begin to see errors as well. This is a tightly coupled architecture. 


> A more reliable architecture is loosely coupled. This is an architecture where if one component fails, it is isolated and therefore won't cause cascading failures throughout the whole system. If we coded the application to use a more loosely coupled architecture, it could look as follows. 


> Just like our cashier and barista, we introduced a buffer between the two. In this case, we introduced a message queue. Messages are sent into the queue by Application A and they are processed by Application B. If Application B fails, Application A doesn't experience any disruption. Messages being sent can still be sent to the queue and will remain there until they are eventually processed. 

> This is loosely coupled. This is what we strive to achieve with architectures on AWS. And this brings me to two AWS services that can assist in this regard. **Amazon Simple Queue Service** or **SQS** and **Amazon Simple Notification Service** or **SNS**. But before I dive into those two services, let me just order a to-go coffee on our cafe website. Done. All right, well, that's great. I should get a message when that order is ready. 

> First up, let's discuss Amazon SQS. SQS allows you to send, store, and receive messages between software components at any volume. This is without losing messages or requiring other services to be available. Think of messages as our coffee orders and the order board as an SQS queue. Messages have the person's name, coffee order, and time they ordered. The data contained within a message is called a payload, and it's protected until delivery. SQS queues are where messages are placed until they are processed. And AWS manages the underlying infrastructure for you to host those queues. These scale automatically, are reliable, and are easy to configure and use. 


> Now, Amazon SNS is similar in that it is used to send out messages to services, but it can also send out notifications to end users. It does this in a different way called a publish/subscribe or pub/sub model. This means that you can create something called an SNS topic which is just a channel for messages to be delivered. You then configure subscribers to that topic and finally publish messages for those subscribers. In practice, that means you can send one message to a topic which will then fan out to all the subscribers in a single go. These subscribers can also be endpoints such as SQS queues, AWS Lambda functions, and HTTPS or HTTP web hooks. 


> Additionally, SNS can be used to fan out notifications to end users using mobile push, SMS, and email. Taking this back to our coffee shop, we could send out a notification when a customer's order is ready. This could be a simple SMS to let them know to pick it up or even a mobile push. 

> In fact, it looks like my phone just received a message. Looks like my order is ready. See you soon.

### Monolithic applications and microservices

<div align="center">
<img src=https://i.imgur.com/DCsAVzu.png width=50%>
</div>

Applications are made of multiple components. The components communicate with each other to transmit data, fulfill requests, and keep the application running. 

Suppose that you have an application with tightly coupled components. These components might include databases, servers, the user interface, business logic, and so on. This type of architecture can be considered a **monolithic application（單一應用程式）**. 

In this approach to application architecture, if a single component fails, other components fail, and possibly the entire application fails.

> **To help maintain application availability when a single component fails, you can design your application through a microservices approach.**

<div align="center">
<img src=https://i.imgur.com/QDDD19D.png width=50%>
</div>

In a microservices approach, application components are loosely coupled. In this case, if a single component fails, the other components continue to work because they are communicating with each other. The loose coupling prevents the entire application from failing. 

When designing applications on AWS, you can take a microservices approach with services and components that fulfill different functions. Two services facilitate application integration: Amazon Simple Notification Service (Amazon SNS) and Amazon Simple Queue Service (Amazon SQS).

### Amazon Simple Notification Service (Amazon SNS)

Amazon Simple Notification Service (Amazon SNS) is a publish/subscribe service. Using Amazon SNS topics, a publisher publishes messages to subscribers. This is similar to the coffee shop; the cashier provides coffee orders to the barista who makes the drinks.

In Amazon SNS, subscribers can be web servers, email addresses, AWS Lambda functions, or several other options. 

Step 1: Publishing updates from a single topic

<div align="center">
<img src=https://i.imgur.com/JfWdMUy.png width=60%>
</div>

Suppose that the coffee shop has a single newsletter that includes updates from all areas of its business. It includes topics such as coupons, coffee trivia, and new products. All of these topics are grouped because this is a single newsletter. All customers who subscribe to the newsletter receive updates about coupons, coffee trivia, and new products.

After a while, some customers express that they would prefer to receive separate newsletters for only the specific topics that interest them. The coffee shop owners decide to try this approach.

Step 2: Publishing updates from multiple topics

<div align="center">
<img src=https://i.imgur.com/OF5rsp2.png width=60%>
</div>

Now, instead of having a single newsletter for all topics, the coffee shop has broken it up into three separate newsletters. Each newsletter is devoted to a specific topic: coupons, coffee trivia, and new products.

Subscribers will now receive updates immediately for only the specific topics to which they have subscribed.

It is possible for subscribers to subscribe to a single topic or to multiple topics. For example, the first customer subscribes to only the coupons topic, and the second subscriber subscribes to only the coffee trivia topic. The third customer subscribes to both the coffee trivia and new products topics.

### Amazon Simple Queue Service (Amazon SQS)

Amazon Simple Queue Service (Amazon SQS) is a message queuing service. 

Using Amazon SQS, you can send, store, and receive messages between software components, without losing messages or requiring other services to be available. In Amazon SQS, an application sends messages into a queue. A user or service retrieves a message from the queue, processes it, and then deletes it from the queue.


Step1 : Example: Fulfilling an order

<div align="center">
<img src=https://i.imgur.com/PfouxkX.png width=60%>
</div>

Suppose that the coffee shop has an ordering process in which a cashier takes orders, and a barista makes the orders. Think of the cashier and the barista as two separate components of an application. 

First, the cashier takes an order and writes it down on a piece of paper. Next, the cashier delivers the paper to the barista. Finally, the barista makes the drink and gives it to the customer.

When the next order comes in, the process repeats. This process runs smoothly as long as both the cashier and the barista are coordinated.

What might happen if the cashier took an order and went to deliver it to the barista, but the barista was out on a break or busy with another order? The cashier would need to wait until the barista is ready to accept the order. This would cause delays in the ordering process and require customers to wait longer to receive their orders.

As the coffee shop has become more popular and the ordering line is moving more slowly, the owners notice that the current ordering process is time consuming and inefficient. They decide to try a different approach that uses a queue.

Step 2: Example: Orders in a queue

<div align="center">
<img src=https://i.imgur.com/DqKNK7V.jpg width=60%>
</div>

Recall that the cashier and the barista are two separate components of an application. A message queuing service such as Amazon SQS enables messages between decoupled application complements.

In this example, the first step in the process remains the same as before: a customer places an order with the cashier. 

The cashier puts the order into a queue. You can think of this as an order board that serves as a buffer between the cashier and the barista. Even if the barista is out on a break or busy with another order, the cashier can continue placing new orders into the queue. 

Next, the barista checks the queue and retrieves the order.

The barista prepares the drink and gives it to the customer. 

The barista then removes the completed order from the queue. 

While the barista is preparing the drink, the cashier is able to continue taking new orders and add them to the queue.

**Simple Test**

Which AWS service is the best choice for publishing messages to subscribers?

[ ] Amazon Simple Queue Service (Amazon SQS)
[ ] Amazon EC2 Auto Scaling
[ ] Amazon Simple Notification Service (Amazon SNS)
[ ] Elastic Load Balancing

## Additional compute services

**Video transcript**

> EC2 instances are virtual machines that you can provision with minimal friction to get up and running on AWS. EC2 is great for all sorts of different use cases like running basic web servers to running high performance computing clusters and everything in between. 


> That being said, though EC2 is incredibly flexible, reliable, and scalable, depending on your use case, you might be looking at alternatives for your compute capacity. EC2 requires that you set up and manage your fleet of instances over time. When you're using EC2, you are responsible for patching your instances when new software packages come out, setting up the scaling of those instances as well as ensuring that you've architected your solutions to be hosted in a highly available manner. This is still not as much management as you would have if you hosted these on-premises. But management processes will still need to be in place. 


> You might be wondering what other services does AWS offer for compute that are more convenient from a management perspective. This is where the term serverless comes in. AWS offers multiple serverless compute options. Serverless means that you cannot actually see or access the underlying infrastructure or instances that are hosting your application. Instead, all the management of the underlying environment from a provisioning, scaling, high availability, and maintenance perspective are taken care of for you. All you need to do is focus on your application and the rest is taken care of. 


> AWS Lambda is one serverless compute option. Lambda's a service that allows you to upload your code into what's called a Lambda function. Configure a trigger and from there, the service waits for the trigger. When the trigger is detected, the code is automatically run in a managed environment, an environment you do not need to worry too much about because it is automatically scalable, highly available and all of the maintenance in the environment itself is done by AWS. If you have one or 1,000 incoming triggers, Lambda will scale your function to meet demand. Lambda is designed to run code under 15 minutes so this isn't for long running processes like deep learning. It's more suited for quick processing like a web backend, handling requests or a backend expense report processing service where each invocation takes less than 15 minutes to complete. 


> If you weren't quite ready for serverless yet or you need access to the underlying environment, but still want efficiency and portability, you should look at AWS container services like Amazon Elastic Container Service, otherwise known as ECS. Or Amazon Elastic Kubernetes Service, otherwise known as EKS. 


> Both of these services are container orchestration tools, but before I get too far here, a container in this case is a Docker container. Docker is a widely used platform that uses operating system level virtualization to deliver software in containers. Now a container is a package for your code where you package up your application, its dependencies as well as any configurations that it needs to run. These containers run on top of EC2 instances and run in isolation from each other similar to how virtual machines work. But in this case, the host is an EC2 instance. When you use Docker containers on AWS, you need processes to start, stop, restart, and monitor containers running across not just one EC2 instance, but a number of them together which is called a cluster. 


> The process of doing these tasks is called container orchestration and it turns out it's really hard to do on your own. Orchestration tools were created to help you manage your containers. ECS is designed to help you run your containerized applications at scale without the hassle of managing your own container orchestration software. EKS does a similar thing, but uses different tooling and with different features. 


> Both Amazon ECS and Amazon EKS can run on top of EC2. But if you don't want to even think about using EC2s to host your containers because you either don't need access to the underlying OS or you don't want to manage those EC2 instances, you can use a compute platform called AWS Fargate. Fargate is a serverless compute platform for ECS or EKS. That's a bit high level and it might be confusing, so let's clear that up. 


> If you are trying to host traditional applications and want full access to the underlying operating system like Linux or Windows, you are going to want to use EC2. If you are looking to host short running functions, service-oriented or event driven applications and you don't want to manage the underlying environment at all, look into the serverless AWS Lambda. If you are looking to run Docker container-based workloads on AWS, you first need to choose your orchestration tool. Do you want to use Amazon ECS or Amazon EKS? After you choose your tool, you then need to chose your platform. Do you want to run your containers on EC2 instances that you manage or in a serverless environment like AWS Fargate that is managed for you? 


> Those are just some of your compute options with AWS and it's not even a complete list. Check out the notes for more information on AWS compute services as well as others that we didn't get to talk about in this video.

### Serverless computing（無服務器計算）

Earlier in this module, you learned about Amazon EC2, a service that lets you run virtual servers in the cloud. If you have applications that you want to run in Amazon EC2, you must do the following:

1. Provision instances (virtual servers)，配置實例（虛擬服務器）.
2. Upload your code.
3. Continue to manage the instances while your application is running.

<div align="center">
<img src=https://i.imgur.com/fXpkrCw.png width=60%>
</div>


The term “serverless” means that your code runs on servers, but you do not need to provision or manage these servers. With serverless computing, you can focus more on innovating new products and features instead of maintaining servers.

Another benefit of serverless computing is the flexibility to scale serverless applications automatically. Serverless computing can adjust the applications' capacity by modifying the units of consumptions, such as throughput and memory. 

An AWS service for serverless computing is **AWS Lambda**.

### AWS Lambda

[AWS Lambda](https://aws.amazon.com/lambda) is a service that lets you run code without needing to provision or manage servers. 

> AWS Lambda 是一種無伺服器、事件推動的運算服務，可讓您針對幾乎任何類型的應用程式或後端服務執行程式碼，而無需佈建或管理伺服器。您可以從超過 200 個 AWS 服務和軟體即服務 (SaaS) 應用程式觸發 Lambda，且僅需針對所使用的服務付費。 
> 
> 使用案例
> 
> **大規模處理資料**
> 根據需要以您需要的容量執行程式碼。自動擴展以匹配您的資料量並啟用自訂事件觸發器。
> 
> **執行互動式 Web 和行動後端**
> 將 AWS Lambda 與其他 AWS 服務組合，以建立安全、穩定且可擴展的線上體驗。
> 
> **啟用強大的 ML Insights**
> 預處理資料，然後再將其提供給機器學習 (ML) 模型。藉由 Amazon Elastic File System (EFS) 存取，AWS Lambda 處理基礎設施管理和佈建來簡化擴展。
> 
> **建立事件驅動的應用程式**
> 建置事件驅動的功能，以在解偶的服務之間輕鬆通訊。透過在需求高峰期執行應用程式來降低成本，而不會導致資源崩潰或過度佈建。


While using AWS Lambda, you pay only for the compute time that you consume. Charges apply only when your code is running. You can also run code for virtually any type of application or backend service, all with zero administration. 

For example, a simple Lambda function might involve automatically resizing uploaded images to the AWS Cloud. In this case, the function triggers when uploading a new image. 

### How AWS Lambda works

<div align="center">
<img src=https://i.imgur.com/3ZZlJz9.png width=80%>
</div>

1. You upload your code to Lambda. 
2. You set your code to trigger from an event source, such as AWS services, mobile applications, or HTTP endpoints.
3. Lambda runs your code only when triggered.
4. You pay only for the compute time that you use. In the previous example of resizing images, you would pay only for the compute time that you use when uploading new images. Uploading the images triggers Lambda to run code for the image resizing function.


> **In AWS, you can also build and run containerized applications.**

### Containers

Containers provide you with a standard way to package your application's code and dependencies into a single object. You can also use containers for processes and workflows in which there are essential requirements for security, reliability, and scalability.

Step 1: One host with multiple containers

<div align="center">
<img src=https://i.imgur.com/sHYLCk3.png width=50%>
</div>

Suppose that a company’s application developer has an environment on their computer that is different from the environment on the computers used by the IT operations staff. The developer wants to ensure that the application’s environment remains consistent regardless of deployment, so they use a containerized approach. This helps to reduce time spent debugging applications and diagnosing differences in computing environments.

Step 2: Tens of hosts with hundreds of containers

<div align="center">
<img src=https://i.imgur.com/uwU6jWJ.png width=50%>
</div>


When running containerized applications, it’s important to consider scalability. Suppose that instead of a single host with multiple containers, you have to manage tens of hosts with hundreds of containers. Alternatively, you have to manage possibly hundreds of hosts with thousands of containers. At a large scale, imagine how much time it might take for you to monitor memory usage, security, logging, and so on.

總結
Container orchestration services help you to deploy, manage, and scale your containerized applications. Next, you will learn about two services that provide container orchestration: Amazon Elastic Container Service and Amazon Elastic Kubernetes Service.

### Amazon Elastic Container Service (Amazon ECS)

[Amazon Elastic Container Service (Amazon ECS)](https://aws.amazon.com/ecs/) is a highly scalable, high-performance container management system that enables you to run and scale containerized applications on AWS. 

> 運作方式
> 
> Amazon ECS 是一種全受管容器協同運作服務，可輕鬆地讓您部署、管理和擴展容器化應用程式。 
> 
> ![](https://i.imgur.com/3MYMtUd.png)
> [了解 Amazon ECS 的運作方式](https://aws.amazon.com/tw/ecs/features/?pg=ln&sec=gs)

Amazon ECS supports Docker containers. Docker is a software platform that enables you to build, test, and deploy applications quickly. AWS supports the use of open-source Docker Community Edition and subscription-based Docker Enterprise Edition. With Amazon ECS, you can use API calls to launch and stop Docker-enabled applications.

### Amazon Elastic Kubernetes Service (Amazon EKS)

>  運作方式
> 
> Amazon Elastic Kubernetes Service (Amazon EKS) 是一項受管容器服務，可在雲端或內部部署系統中啟動、執行和擴展 Kubernetes 應用程式。 
> 
> 在雲端環境中使用Amazon EKS
> ![](https://i.imgur.com/2YC3JPS.png)
> 
> [Amazon EKS 官網](https://aws.amazon.com/tw/eks/)

Amazon Elastic Kubernetes Service (Amazon EKS) is a fully managed service that you can use to run Kubernetes on AWS. 

Kubernetes is open-source software that enables you to deploy and manage containerized applications at scale. A large community of volunteers maintains Kubernetes, and AWS actively works together with the Kubernetes community. As new features and functionalities release for Kubernetes applications, you can easily apply these updates to your applications managed by Amazon EKS.

### AWS Fargate(容器的無伺服器運算)

[AWS Fargate](https://aws.amazon.com/tw/fargate/) is a serverless compute engine for containers. It works with both Amazon ECS and Amazon EKS. 

> AWS Fargate 是無伺服器，依用量計費的運算引擎，讓您專注於建置應用程式，而無需管理伺服器。AWS Fargate 適用於搭配 Amazon Elastic Container Service (ECS) 和 Amazon Elastic Kubernetes Service (EKS) 使用。
> 
> 

When using AWS Fargate, you do not need to provision or manage servers. AWS Fargate manages your server infrastructure for you. You can focus more on innovating and developing your applications, and you pay only for the resources that are required to run your containers.


## Module 2 summary

In Module 2, you learned about the following concepts:

* Amazon EC2 instance types and pricing options
* Amazon EC2 Auto Scaling
* Elastic Load Balancing
* AWS services for messaging, containers, and serverless computing

**Video transcript**

> Hey everyone, I hope you've been enjoying the course so far. We're going to do check-ins like this one after each major topic to review what you've learned. 


> First things first, what is cloud computing and what does AWS offer? We define cloud computing as the on-demand delivery of IT resources over the internet with pay-as-you-go pricing. This means that you can make requests for IT resources like compute, networking, storage, analytics, or other types of resources, and then they're made available for you on demand. You don't pay for the resource upfront. Instead, you just provision and pay at the end of the month. 


> AWS offers services and many categories that you use together to create your solutions. We've only covered a few services so far, you learned about Amazon EC2. With EC2, you can dynamically spin up and spin down virtual servers called EC2 instances. When you launch an EC2 instance, you choose the instance family. The instance family determines the hardware the instance runs on. 


> And you can have instances that are built for your specific purpose. The categories are general purpose, compute optimized, memory optimized, accelerated computing, and storage optimized. 


> You can scale your EC2 instances either vertically by resizing the instance, or horizontally by launching new instances and adding them to the pool. You can set up automated horizontal scaling, using Amazon EC2 Auto Scaling. 


> Once you've scaled your EC2 instances out horizontally, you need something to distribute the incoming traffic across those instances. This is where the Elastic Load Balancer comes into play. 

> EC2 instances have different pricing models. There is On-Demand, which is the most flexible and has no contract, spot pricing, which allows you to utilize unused capacity at a discounted rate, Savings Plans or Reserved Instances, which allow you to enter into a contract with AWS to get a discounted rate when you commit to a certain level of usage, and Savings Plans which apply to AWS Lambda, and AWS Fargate, as well as EC2 instances. 


> We also covered messaging services. There is Amazon Simple Queue Service or SQS. This service allows you to decouple system components. Messages remain in the queue until they are either consumed or deleted. Amazon Simple Notification Service or SNS, is used for sending messages like emails, text messages, push notifications, or even HTTP requests. Once a message is published, it is sent to all of these subscribers. 


> You also learned that AWS has different types of compute services beyond just virtual servers like EC2. There are container services like Amazon Elastic Container Service, or ECS. And there's Amazon Elastic Kubernetes Service, or EKS. Both of which are container orchestration tools. You can use these tools with EC2 instances, but if you don't want to manage that, you don't need to. 


> You can use AWS Fargate, which allows you to run your containers on top of a serverless compute platform. Then there is AWS Lambda, which allows you to just upload your code, and configure it to run based on triggers. And you only get charged for when the code is actually running. No containers, no virtual machines. Just code and configuration. 

> Hopefully that sums it up. Catch you in the next one.

### Additional resources

To learn more about the concepts that were explored in Module 2, review these resources.

* [Compute on AWS](https://aws.amazon.com/products/compute)
* [AWS Compute Blog](https://aws.amazon.com/blogs/compute/)
* [AWS Compute Services](https://docs.aws.amazon.com/whitepapers/latest/aws-overview/compute-services.html)
* [Hands-On Tutorials: Compute](https://aws.amazon.com/getting-started/hands-on/?awsf.getting-started-category=category%23compute&awsf.getting-started-content-type=content-type%23hands-on)
* [Category Deep Dive: Serverless](https://aws.amazon.com/getting-started/deep-dive-serverless/)
* [AWS Customer Stories: Serverless](https://aws.amazon.com/solutions/case-studies/?customer-references-cards.sort-by=item.additionalFields.publishedDate&customer-references-cards.sort-order=desc&awsf.customer-references-location=*all&awsf.customer-references-segment=*all&awsf.customer-references-product=product%23vpc%7Cproduct%23api-gateway%7Cproduct%23cloudfront%7Cproduct%23route53%7Cproduct%23directconnect%7Cproduct%23elb&awsf.customer-references-category=category%23serverless)



## Module 2 quiz

Test your knowledge of some of the key concepts from this module by answering the questions in this quiz.

### Knowledge check

1. You want to use an Amazon EC2 instance for a batch processing workload. What would be the best Amazon EC2 instance type to use?

[ ] General purpose
[ ] Memory optimized
[ ] Compute optimized
[ ] Storage optimized

2. What are the contract length options for Amazon EC2 Reserved Instances? (Select TWO.)

[ ] 1 year [ ] 2 years [ ] 3 years [ ] 4 years [ ] 5 years


3. You have a workload that will run for a total of 6 months and can withstand interruptions. What would be the most cost-efficient Amazon EC2 purchasing option?

[ ]Reserved Instance
[ ]Spot Instance
[ ]Dedicated Instance
[ ]On-Demand Instance

4. Which process is an example of Elastic Load Balancing?

[ ] Ensuring that no single Amazon EC2 instance has to carry the full workload on its own
[ ] Removing unneeded Amazon EC2 instances when demand is low
[ ] Adding a second Amazon EC2 instance during an online store’s popular sale
[ ] Automatically adjusting the number of Amazon EC2 instances to meet demand

5. You want to deploy and manage containerized applications. Which service should you use?

[ ]AWS Lambda
[ ]Amazon Simple Notification Service (Amazon SNS)
[ ]Amazon Simple Queue Service (Amazon SQS)
[ ]Amazon Elastic Kubernetes Service (Amazon EKS)

# Module 3: Global Infrastructure and Reliability

## Module 3 introduction

### Learning objectives

In this module, you will learn how to:

* Summarize the benefits of the AWS Global Infrastructure.
* Describe the basic concept of Availability Zones.
* Describe the benefits of Amazon CloudFront and edge locations.
* Compare different methods for provisioning AWS services.

**Video transcript**

> I want to talk to you about high availability. Say you wanna grab a cup of coffee at the cafe, but today is not just a normal day in our city. Today, there is a parade coming to march down our street in celebration of all of the wonderful cloud migrations that have been successful. This parade is going to march right in front of our shop. This is great because who doesn't love to look at floats and balloons and have someone throw candy at them from the street? But this is also bad because while the parade is coming down the street, our customers who are driving to come get coffee will be diverted and won't be able to stop by the shop. This will drive sales down and also make customers unhappy. 


> Luckily for us, we thought ahead. We thought long ago what would happen if for some reason our customers couldn't make it into the shop temporarily? Like if there was a parade or if there's a flood or some other event that blocks us from getting into the shop? Well, no matter the reason, we need to be highly available for our customers. 


> So, I'll let you in on a secret. This isn't our coffee shop's only location. The cafe is actually a chain and we have locations all around the city. That way, if a parade comes down the street, or if there was a power outage on our block, no worries. Customers can still get their coffee by visiting one of our shops just a few blocks away. We still make money and they get their coffee. All is well. 


> AWS has done a similar thing with how the AWS global infrastructure is set up. It's not good enough to have one giant data center where all of the resources are. If something were to happen to that data center, like a power outage or a natural disaster, everyone's applications would go down all at once. You need high availability and fault tolerance. 

> Turns out, it's not even good enough to have two giant data centers. Instead, AWS operates in all sorts of different areas around the world called Regions. We're going to talk about this in depth in upcoming videos. In the meantime, I'm gonna sit here and relax, because I know my business is highly available regardless of any parades blocking the street.

### Building a global footprint

To understand the AWS global infrastructure(全球基礎設施), consider the coffee shop. If an event such as a parade, flood, or power outage impacts one location, customers can still get their coffee by visiting a different location only a few blocks away.

This is similar to how the AWS global infrastructure works.

## AWS global infrastructure

**Video transcript** 

> To understand the global infrastructure AWS, I wanna begin with your fundamental business need. You have an application that you have to run, or content you need stored, or data you need analyzed. Basically you have stuff that has to live and operate somewhere. Now historically, businesses had to run applications in their own data centers, 'cause they didn't have a choice. Once AWS became available, companies like yours could now run their applications in other data centers they didn't actually own. 


> But the conversation is so much more than that, 'cause I want you to understand a fundamental problem with any data center, doesn't matter who built it or who owns it. Events can happen that could cause you to lose connection to that building. If you run your own data center, you have to figure out how to answer the question of what will you do when disaster strikes your building. You could run a second data center, but real estate prices alone could stop you, much less all the duplicate expense of hardware, employees, electricity, heating and cooling, security. Most businesses simply end up just storing backups somewhere, and then hope for the disaster to never come. And hope is not a good business plan. 


> AWS answers the question of what happens when disaster strikes by building our data centers in large groups we call Regions, and here's how it's designed. 


> Throughout the globe, AWS builds Regions to be closest to where the business traffic demands. Locations like Paris, Tokyo, Sao Paulo, Dublin, Ohio. Inside each Region, we have multiple data centers that have all the compute, storage, and other services you need to run your applications. Each Region can be connected to each other Region through a high speed fiber network, controlled by AWS, a truly global operation from corner to corner if you need it to be. Now before we get into the architecture of how each Region is built, it's important to know that you, the business decision maker, gets to choose which Region you want to run out of. And each Region is isolated from every other Region in the sense that absolutely no data goes in or out of your environment in that Region without you explicitly granting permission for that data to be moved. This is a critical security conversation to have. 


> For example, you might have government compliance requirements that your financial information in Frankfurt cannot leave Germany. Well this is absolutely the way AWS operates outta the box. Any data stored in the Frankfurt Region never leaves the Frankfurt Region, or data in the London region never leaves London, or Sydney never leaves Sydney, unless you explicitly, with the right credentials and permissions, request the data be exported. 


> Regional data sovereignty is part of the critical design of AWS Regions. With data being subject to the local laws and statutes of the country where the Region lives. So with that understanding, that your data, your application, lives and runs in a Region, one of the first decisions you get to make is which Region do you pick? There's four business factors that go into choosing a Region. 


> Number one, **compliance**. Before any of the other factors, you must first look at your compliance requirements. Do you have a requirement your data must live in UK boundaries? Then you should choose the London Region, full stop. None of the rest of the options matter. Or let's say you must run inside Chinese borders. Well then, you should choose on of our Chinese Regions. Most businesses, though, are not governed by such strict regulations. So if you don't have a compliance or regulatory control that dictates your Region, then you can look at the other factors. 


> Number two, **proximity**. How close you are to your customer base is a major factor because speed of light, still the law of the universe. If most of your customers live in Singapore, consider running out of the Singapore Region. Now you certainly can run out of Virginia, but the time it takes for the information to be sent, or latency, between the US and Singapore is always going to be a factor. Now we may be developing quantum computing, but quantum networking, still some ways away. The time it takes light to travel around the world is always a consideration. Locating close to your customer base, usually the right call. 


> Number three, **feature availability**. Sometimes the closest Region may not have all the AWS features you want. Now here's one of the cool things about AWS. We are constantly innovating on behalf of our customers. Every year, AWS releases thousands of new features and products specifically to answer customer requests and needs. But sometimes those brand new services take a lot of new physical hardware that AWS has to build out to make the service operational. And sometimes that means we have to build the service out one Region at a time. So let's say your developers wanted to play with Amazon Braket, our new quantum computing platform. Well then, they have to run in the Regions that already have the hardware installed. Eventually, can we expect it to be in every Region? Well, yeah, that's a good expectation, but if you wanna use it today, then that might be your deciding factor. 


> Number four, **pricing**. Even when the hardware is equal one Region to the next, some locations are just more expensive to operate in, for example, Brazil. Now Brazil's tax structure is such that it costs AWS significantly more to operate the exact same services there than in many other countries. The exact same workload in Sao Paulo might be, let's say, 50% more expensive to run than out of Oregon in the United States. Price can be determined by many factors, so AWS has very transparent granular pricing that we'll continue to discuss in this class. But know that each Region has a different price sheet. So if budget is your primary concern, even if your customers live in Brazil, you might still wanna operate in a different country, again, if price is your primary motivation. 


> So four key factors to choose a Region: Compliance, proximity, feature availability, and pricing. When we come back, we'll look at the moving parts inside a Region.

### Selecting a Region

When determining the right Region for your services, data, and applications, consider the following four business factors. 

* **Compliance with data governance and legal requirements（遵守數據治理和法律要求）**

    Depending on your company and location, you might need to run your data out of specific areas. For example, if your company requires all of its data to reside within the boundaries of the UK, you would choose the London Region. 

    Not all companies have location-specific data regulations, so you might need to focus more on the other three factors.
    
* **Proximity to your customers（貼近您的客戶）**

    Selecting a Region that is close to your customers will help you to get content to them faster. For example, your company is based in Washington, DC, and many of your customers live in Singapore. You might consider running your infrastructure in the Northern Virginia Region to be close to company headquarters, and run your applications from the Singapore Region.
    
* **Available services within a Region（區域內可用的服務）**

    Sometimes, the closest Region might not have all the features that you want to offer to customers. AWS is frequently innovating by creating new services and expanding on features within existing services. However, making new services available around the world sometimes requires AWS to build out physical hardware one Region at a time. 

    Suppose that your developers want to build an application that uses Amazon Braket (AWS quantum computing platform). As of this course, Amazon Braket is not yet available in every AWS Region around the world, so your developers would have to run it in one of the Regions that already offers it.

* **Pricing（價錢）**

    Suppose that you are considering running applications in both the United States and Brazil. The way Brazil’s tax structure is set up, it might cost 50% more to run the same workload out of the São Paulo Region compared to the Oregon Region. You will learn in more detail that several factors determine pricing, but for now know that the cost of services can vary from Region to Region.
    
### Availability Zones

<div align="center">
<img src=https://i.imgur.com/rBt04rV.png width=80%>
</div>


**Video transcript**

> If a Region is where all of the pieces and parts of your application live, some of you might be thinking that we never actually solved the problem that we presented in the last video. Let me restate the problem. You don't want to run your application in a single building because a single building can fail for any number of unavoidable reasons. 


> You may be thinking, if my business needs to be disaster proof, then it can't run in just one location. Well, you're absolutely correct. AWS agrees with that statement and that's why our Regions are not one location. To begin with, AWS has data centers, lots of data centers, all around the world, and each Region is made up of multiple data centers. 


> AWS calls a single data center or a group of data centers, an Availability Zone or AZ. Each Availability Zone is one or more discrete data centers with redundant power, networking, and connectivity. When you launch an Amazon EC2 instance, it launches a virtual machine on a physical hardware that is installed in an Availability Zone. This means each AWS Region consists of multiple isolated and physically separate Availability Zones within a geographic Region.
 

> But we don't build Availability Zones right next to each other because if a large scale incident were to occur, like a natural disaster, for example, you could lose connectivity to everything in that Availability Zone. The question what happens in case of a disaster matters and if you are familiar with disaster recovery planning, you might even have an idea of where we are going with this. 


> If you only run one EC2 instance, it only runs in one building, or one Availability Zone and a large scale disaster occurs, will your application still be able to run and serve your business? The obvious solution to this is to run multiple EC2 instances, just like we showed in the scaling example earlier. But the main thing is don't run them in the same building. Don't even run them in the same street, push them as far apart as you can before the speed of light tells you to stop if you still want low latency communication. Turns out that the speed of light will let us move these Availability Zones tens of miles apart from each other and still keep single digit millisecond latency between these Availability Zones. Now, if a disaster strikes, your application continues just fine because this disaster only knocked over some of your capacity, not all. 


> And as we saw in the last section, you can rapidly spin up more capacity in the remaining Availability Zones, thus allowing your business to continue operating without interruption. And as a best practice with AWS, we always recommend you run across at least two Availability Zones in a Region. This means redundantly deploying your infrastructure in two different AZs. 


> But there's more to Regions than just places to run EC2. Many of the AWS services run at the Region level, meaning they run synchronously across multiple AZs without any additional effort on your part. Take the ELB we talked about previously. This is actually a regional construct. It runs across all Availability Zones, communicating with the EC2 instances that are running in a specific Availability Zone. Regional services are by definition already highly available at no additional cost of effort on your part. 


> So as you plan for high availability, any service that is listed as a regionally scoped service, you'll already have that box checked. When we come back, let's look at going outside the Regions for additional solutions.




An Availability Zone is a single data center or a group of data centers within a Region. Availability Zones are located tens of miles apart from each other. This is close enough to have low latency (the time between when content requested and received) between Availability Zones. However, if a disaster occurs in one part of the Region, they are distant enough to reduce the chance that multiple Availability Zones are affected.

### Running Amazon EC2 instances in multiple Availability Zones

**Amazon EC2 instance in a single Availability Zone**

<div align="center">
<img src=https://i.imgur.com/Vu6a0ff.png width=50%>
</div>


Suppose that you’re running an application on a single Amazon EC2 instance in the Northern California Region. The instance is running in the us-west-1a Availability Zone. If us-west-1a were to fail, you would lose your instance. 



**Amazon EC2 instances in multiple Availability Zones**

<div align="center">
<img src=https://i.imgur.com/abG4JpB.png width=50%>
</div>

A best practice is to run applications across at least two Availability Zones in a Region. In this example, you might choose to run a second Amazon EC2 instance in us-west-1b.

**Availability Zone failure**


<div align="center">
<img src=https://i.imgur.com/1iHLnjv.png width=50%>
</div>


If us-west-1a were to fail, your application would still be running in us-west-1b.

### Knowledge check

Which statement best describes an Availability Zone?

[ ] A geographical area that contains AWS resources
[ ] A single data center or group of data centers within a Region
[ ] A data center that an AWS service uses to perform service-specific operations
[ ] A service that you can use to run AWS infrastructure within your own on-premises data center in a hybrid approach

## Edge locations

**Video transcript**

> One of the great things about the AWS global infrastructure, is the way it's engineered to help you better serve your customers. Remember when selecting a Region, one of the major criteria was proximity to your customers, but what if you have customers all over the world or in cities that are not close to one of our Regions? Well, think about our coffee shop. If you have a good customer base in a new city, you can build a satellite store to service those customers. 


> You don't need to build an entire new headquarters or from an IT perspective, if you have customers in Mumbai who need access to your data, but the data is hosted out of the Tokyo Region, rather than having all the Mumbai-based customers, send requests all the way to Tokyo, to access the data, just place a copy locally or cache a copy in Mumbai. Caching copies of data closer to the customers all around the world uses the concept of content delivery networks, or CDNs. 


> CDNs are commonly used, and on AWS, we call our CDN Amazon CloudFront. **Amazon CloudFront** is a service that helps deliver data, video, applications, and APIs to customers around the world with low latency and high transfer speeds. Amazon CloudFront uses what are called Edge locations, all around the world, to help accelerate communication with users, no matter where they are. 


> Edge locations are separate from Regions, so you can push content from inside a Region to a collection of Edge locations around the world, in order to accelerate communication and content delivery. AWS Edge locations, also run more than just CloudFront. They run a domain name service, or DNS, known as **Amazon Route 53**, helping direct customers to the correct web locations with reliably low latency.

> But what if your business wants to use, AWS services inside their own building? Well sure. AWS can do that for you. Introducing **AWS Outposts**, where AWS will basically install a fully operational mini Region, right inside your own data center. That's owned and operated by AWS, using 100% of AWS functionality, but isolated within your own building. It's not a solution most customers need, but if you have specific problems that can only be solved by staying in your own building, we understand, AWS Outposts can help. 


> All right, there is so much more that we can say about AWS global infrastructure, but let's keep it simple and stop here. So here's the key points. Number one, Regions are geographically isolated areas, where you can access services needed to run your enterprise. Number two, Regions contain Availability Zones, that allow you to run across physically separated buildings, tens of miles of separation, while keeping your application logically unified. Availability Zones help you solve high availability and disaster recovery scenarios, without any additional effort on your part, and number three, AWS Edge locations run Amazon CloudFront to help get content closer to your customers, no matter where they are in the world.

## Edge locations

An edge location is a site that Amazon CloudFront uses to store cached copies of your content closer to your customers for faster delivery.


![](https://i.imgur.com/oQOPZRL.png)

**Origin**

Suppose that your company's data is stored in Brazil,and you have customers who live in China. To provide content to these customers, you don't need to move all the content to one of the Chinese Regions.

**Edge Location**

Instead of requiring your customers to get ther data from Brazil, you can cache a copy locally at an edge location that is close to your customers in China.

**Customer** 

When a customer in China requests one of your files,Amazon CloudFront retrieves the file from the cache in the edge location and delivers the file to the customer. Thefile is delivered to the customer faster because it came from the edge location near China instead of the original source in Brazil.


## How to provision AWS resources

**Video transcript**

> We've been talking about a few different AWS resources as well as the AWS global infrastructure. You may be wondering, how do I actually interact with these services? And the answer is APIs. In AWS, everything is an API call. An API is an application programming interface. And what that means is, there are pre determined ways for you to interact with AWS services. And you can invoke or call these APIs to provision, configure, and manage your AWS resources. 


> For example, you can launch an EC2 instance or you can create an AWS Lambda function. Each of those would be different requests and different API calls to AWS. You can use the AWS Management Console, the AWS Command Line Interface, the AWS Software Development Kits, or various other tools like AWS CloudFormation, to create requests to send to AWS APIs to create and manage AWS resources. 


> First, let's talk about the AWS Management Console. The AWS Management Console is browser-based. Through the console, you can manage your AWS resources visually and in a way that is easy to digest. This is great for getting started and building your knowledge of the services. It's also useful for building out test environments or viewing AWS bills, viewing monitoring and working with other non technical resources. The AWS Management Console is most likely the first place you will go when you are learning about AWS. 


> However, once you are up and running in a production type environment, you don't want to rely on the point and click style that the console gives you to create and manage your AWS resources. For example, in order to create an Amazon EC2 Instance, you need to click through various screens, setting all the configurations you want, and then you launch your instance. If later, you wanted to launch another EC2 Instance, you would need to go back into the console and click through those screens again to get it up and running. By having humans do this sort of manual provisioning, you're opening yourself up to potential errors. It's pretty easy to forget to check a checkbox or misspell something when you are doing everything manually. 


> The answer to this problem is to use tools that allow you to script or program the API calls. One tool you can use is the AWS Command Line Interface or CLI. The CLI allows you to make API calls using the terminal on your machine. This is different than the visual navigation style of the Management Console. Writing commands using the CLI makes actions scriptable and repeatable. So, you can write and run your commands to launch an EC2 Instance. And if you want to launch another, you can just run the pre-written command again. This makes it less susceptible to human error. And you can have these scripts run automatically, like on a schedule or triggered by another process. 


> Automation is very important to having a successful and predictable cloud deployment over time. Another way to interact with AWS is through the AWS Software Development Kits or SDKs. The SDKs allow you to interact with AWS resources through various programming languages. This makes it easy for developers to create programs that use AWS without using the low level APIs, as well as avoiding that manual resource creation that we just talked about. More on that in a bit.

### Ways to interact with AWS services**

**AWS Management Console**

The AWS Management Console is a web-based interface for accessing and managing AWS services. You can quickly access recently used services and search for other services by name, keyword, or acronym. The console includes wizards and automated workflows that can simplify the process of completing tasks.

You can also use the AWS Console mobile application to perform tasks such as monitoring resources, viewing alarms, and accessing billing information. Multiple identities can stay logged into the AWS Console mobile app at the same time.

**AWS Command Line Interface** 

To save time when making API requests, you can use the AWS Command Line Interface (AWS CLI). AWS CLI enables you to control multiple AWS services directly from the command line within one tool. AWS CLI is available for users on Windows, macOS, and Linux. 


By using AWS CLI, you can automate the actions that your services and applications perform through scripts. For example, you can use commands to launch an Amazon EC2 instance, connect an Amazon EC2 instance to a specific Auto Scaling group, and more.

**software development kits**

Another option for accessing and managing AWS services is the software development kits (SDKs). SDKs make it easier for you to use AWS services through an API designed for your programming language or platform. SDKs enable you to use AWS services with your existing applications or create entirely new applications that will run on AWS.


To help you get started with using SDKs, AWS provides documentation and sample code for each supported programming language. Supported programming languages include C++, Java, .NET, and more.

**Video transcript**

> All right, let's continue to talk about how to interact with AWS. You have the AWS Management Console, the CLI, and the SDKs, which are all sort of do it yourself ways to provision and manage your AWS environment. If you want to provision a resource, you can log into the console and point and click, you can write some commands, or you can write some programs to do it. There are also other ways you can manage your AWS environment using managed tools like AWS Elastic Beanstalk, and AWS CloudFormation. 


> AWS Elastic Beanstalk is a service that helps you provision Amazon EC2-based environments. Instead of clicking around the console or writing multiple commands to build out your network, EC2 instances, scaling and Elastic Load Balancers, you can instead provide your application code and desired configurations to the AWS Elastic Beanstalk service, which then takes that information and builds out your environment for you. AWS Elastic Beanstalk also makes it easy to save environment configurations, so they can be deployed again easily. AWS Elastic Beanstalk gives you the convenience of not having to provision and manage all of these pieces separately, while still giving you the visibility and control of the underlying resources. You get to focus on your business application, not the infrastructure. 


> Another service you can use to help create automated and repeatable deployments is AWS CloudFormation. AWS CloudFormation is an infrastructure as code tool that allows you to define a wide variety of AWS resources in a declarative way using JSON or YAML text-based documents called CloudFormation templates. A declarative format like this allows you to define what you want to build without specifying the details of exactly how to build it. CloudFormation lets you define what you want and the CloudFormation engine will worry about the details on calling APIs to get everything built out. 


> It also isn't just limited to EC2-based solutions. CloudFormation supports many different AWS resources from storage, databases, analytics, machine learning, and more. Once you define your resources in a CloudFormation template, CloudFormation will parse the template and begin provisioning all the resources you defined in parallel. CloudFormation manages all the calls to the backend AWS APIs for you. You can run the same CloudFormation template in multiple accounts or multiple regions, and it will create identical environments across them. There is less room for human error as it is a totally automated process. 


> To recap, the AWS Management Console is great for learning and providing a visual for the user. The AWS Management Console is a manual tool. So right off the bat, it isn't a great option for automation. You can instead use the CLI to script your interactions with AWS using the terminal. You can use the SDKs to write programs to interact with AWS for you or you can use manage tools like AWS Elastic Beanstalk or AWS CloudFormation.


### AWS Elastic Beanstalk

> AWS Elastic Beanstalk 是一項易用的服務，用於在熟悉的伺服器 (例如 Apache、Nginx、Passenger 和 IIS) 上部署和擴展以 Java、.NET、PHP、Node.js、Python、Ruby、Go 和 Docker 開發的 Web 應用程式和服務。
> 
> 您只需上傳程式碼，Elastic Beanstalk 即可為您自動處理部署，包括容量佈建、負載平衡、自動調整規模，以及應用程式運作狀態監控。同時，您能夠完全控制為應用程式提供支援的 AWS 資源，並可隨時存取基礎資源。
> 
> Elastic Beanstalk 不收取其他費用 – 您只需支付使用 AWS 資源存放和執行應用程式的費用。

With AWS Elastic Beanstalk, you provide code and configuration settings, and Elastic Beanstalk deploys the resources necessary to perform the following tasks:

* Adjust capacity
* Load balancing
* Automatic scaling
* Application health monitoring

### AWS CloudFormation**

>針對同時包含後端資料庫的可擴展 Web 應用程式，您可能會使用 Auto Scaling 群組、Elastic Load Balancing 負載平衡器和 Amazon Relational Database Service 資料庫執行個體。您可能會使用每個個別服務來佈建這些資源，並在建立資源後，必須將其設定為共同運作。在您讓您的應用程式開始執行之前，這些任務可能會先讓一切變得更複雜且更耗費時間。
>
>您可以改為建立或修改現有的 CloudFormation 範本。範本會描述您所有的資源及其屬性。當您使用該範本建立 CloudFormation 堆疊時，CloudFormation 會為您佈建 Auto Scaling 群組、負載平衡器和資料庫。在成功建立堆疊後，您的 AWS 資源便會設定好並開始執行。您仍然可以輕易的刪除堆疊，同時刪除堆疊中所有的資源。使用 CloudFormation，您可以輕鬆的將資源集合做為單一單位管理。
>
>快速複製您的基礎設施
>
>若您的應用程式需要其他可用性，您可能會在多個區域中複製它，以便在一個區域無法使用時，讓您的使用者仍然可以在其他區域使用您的應用程式。複製您應用程式的挑戰是，您必須同時複製您的資源。您不僅需要記錄所有您應用程式所需的資源，還要在每個區域內佈建及設定那些資源。
>
>重複使用您的 CloudFormation 範本，以一致且可重複的方式建立資源。如需再次使用範本，只需要描述您的資源一次，然後在多個區域內重複佈建相同資源即可。

With AWS CloudFormation, you can treat your infrastructure as code. This means that you can build an environment by writing lines of code instead of using the AWS Management Console to individually provision resources.

AWS CloudFormation provisions your resources in a safe, repeatable manner, enabling you to frequently build your infrastructure and applications without having to perform manual actions. It determines the right operations to perform when managing your stack and rolls back changes automatically if it detects errors.

## Module 3 summary

In Module 3, you learned about the following concepts:

* AWS Regions and Availability Zones
* Edge locations and Amazon CloudFront
* The AWS Management Console, AWS CLI, and SDKs
* AWS Elastic Beanstalk
* AWS CloudFormation

**Video transcript**

> Awesome stuff, I mean, we covered a lot of ground in here. And I don't mean that just because we talked about AWS global infrastructure. 

> But seriously, we covered how logical clusters of data centers make up Availability Zones, Availability Zones in turn make up Regions, and those are spread globally. You then choose what Regions and Availability Zones you want to operate out of and as a best practice, you should always deploy infrastructure across at least two Availability Zones. And some AWS services like Elastic Load Balancing, Amazon SQS, and Amazon SNS already do this for you. 

> We also talked about Edge locations and how you can deploy content there to speed up delivery to your customers. We even touched upon edge devices like AWS Outposts which allow you to run AWS infrastructure right in your own data center. 

> Another thing we discussed was how to provision AWS resources through various options, such as the AWS Management Console, the SDK, CLI, AWS Elastic Beanstalk, and AWS CloudFormation, where you learned how you can set up your infrastructure as code. 

> I hope you learned how globally available AWS is and how easy it is to get started with provisioning resources.

### Additional resources

Review these resources to learn more about the concepts that were explored in Module 3.

* [Global Infrastructure](https://aws.amazon.com/about-aws/global-infrastructure/)
* [Interactive map of the AWS Global Infrastructure](https://www.infrastructure.aws/)
* [Regions and Availability Zones](https://aws.amazon.com/about-aws/global-infrastructure/regions_az)
* [AWS Networking and Content Delivery Blog](https://aws.amazon.com/blogs/networking-and-content-delivery/)
* [Tools to Build on AWS](https://aws.amazon.com/tools/)

## Module 3 quiz

Test your knowledge of some of the key concepts from this module by answering the questions in this quiz.

Which statement is TRUE for the AWS global infrastructure?

[ ] Region consists of a single Availability Zone.

[ ] An Availability Zone consists of two or more Regions.

[ ] A Region consists of two or more Availability Zones.

[ ] An Availability Zone consists of a single Region.


Which factors should be considered when selecting a Region? (Select TWO.)

[ ]Compliance with data governance and legal requirements

[ ] Proximity to your customers

[ ] Access to 24/7 technical support

[ ] Ability to assign custom permissions to different users

[ ] Access to the AWS Command Line Interface (AWS CLI)

Which statement best describes Amazon CloudFront?

[ ] A service that enables you to run infrastructure in a hybrid cloud approach

[ ] A serverless compute engine for containers

[ ] A service that enables you to send and receive messages between software components through a queue

[ ] A global content delivery service

Amazon CloudFront 是一項內容交付網路 (CDN) 服務，專為實現高效能、安全性和開發人員便利性而建置。
 
![](https://i.imgur.com/qpMbVKK.png)

Which site does Amazon CloudFront use to cache copies of content for faster delivery to users at any location?

[ ] Region

[ ] Availability Zone

[ ] Edge location

[ ] Origin

Which action can you perform with AWS Outposts?

[ ] Automate actions for AWS services and applications through scripts.

[ ] Access wizards and automated workflows to perform tasks in AWS services.

[ ] Develop AWS applications in supported programming languages.

[ ] Extend AWS infrastructure and services to your on-premises data center.

 AWS Outposts Family 概觀

AWS Outposts 是一系列全受管解決方案，可為幾乎任何內部部署或邊緣位置提供 AWS 基礎設施和服務，以獲得真正一致的混合體驗。 Outposts 解決方案可讓客戶在內部部署擴展和執行原生 AWS 服務，並提供多種外型規格 (從 1U 和 2U Outposts 伺服器至 42U Outposts 機架)，以及多機架部署。

使用 AWS Outposts，您可以在本地執行部分 AWS 服務，並連接至本地 AWS 區域中提供的各種服務。使用熟悉的 AWS 服務、工具和 API 在內部部署執行應用程式和工作負載。Outposts 支援需要低延遲存取內部部署系統的工作負載和裝置、本機資料處理、資料駐留，以及具有本機系統相依性的應用程式遷移。 



# Module 4: Networking

## introduction

**Learning objectives**

In this module, you will learn how to:

* Describe the basic concepts of networking.
* Describe the difference between public and private networking resources. 
* Explain a virtual private gateway using a real life scenario. 
* Explain a virtual private network (VPN) using a real life scenario.
* Describe the benefit of AWS Direct Connect. 
* Describe the benefit of hybrid deployments. 
* Describe the layers of security used in an IT strategy.
* Describe the services customers use to interact with the AWS global network.

**Video transcript**

If we think back to our coffee shop or AWS account, things by now should be running smoothly. Although, what if we had a few eager customers who wanted to give their orders directly to the baristas instead of the cashier out in front? Well, it doesn't make sense to allow every customer to be able to interact with our baristas since they are focused on brewing some fresh caffeinated beverages. So what do we do? 


That's right, kids, say it with me, Amazon Virtual Private Cloud, or VPCs, as they're affectionately known. A VPC lets you provision a logically isolated section of the AWS Cloud where you can launch AWS resources in a virtual network that you define. These resources can be public facing so they have access to the internet, or private with no internet access, usually for backend services like databases or application servers. The public and private grouping of resources are known as subnets and they are ranges of IP addresses in your VPC. 


Now, in our coffee shop, we have different employees and one is a cashier. They take customers' orders and thus we want customers to interact with them, so we put them in what we call a public subnet. Hence they can talk to the customers or the internet. But for our baristas, we want them to focus on making coffee and not interact with customers directly, so we put them in a private subnet. 


Okay, let's get into the next video where we'll dive into networking.

## Connectivity to AWS

**Video transcript**

> A VPC, or Virtual Private Cloud, is essentially your own private network in AWS. A VPC allows you to define your private IP range for your AWS resources, and you place things like EC2 instances and ELBs inside of your VPC. 


> Now you don't just go throw your resources into a VPC and move on. You place them into different subnets. Subnets are chunks of IP addresses in your VPC that allow you to group resources together. Subnets, along with networking rules we will cover later, control whether resources are either publicly or privately available. What we haven't told you yet is there are actually ways you can control what traffic gets into your VPC at all. What I mean by this is, for some VPCs, you might have internet-facing resources that the public should be able to reach, like a public website, for example. 


> However, in other scenarios, you might have resources that you only want to be reachable if someone is logged into your private network. This might be internal services, like an HR application or a backend database. First, let's talk about public-facing resources. In order to allow traffic from the public internet to flow into and out of your VPC, you must attach what is called an internet gateway, or IGW, to your VPC. 


> An internet gateway is like a doorway that is open to the public. Think of our coffee shop. Without a front door, the customers couldn't get in and order their coffee, so we install a front door and the people can then go in and out of that door when coming and going from our shop. The front door in this example is like an internet gateway. Without it, no one can reach the resources placed inside of your VPC. 


> Next, let's talk about a VPC with all internal private resources. We don't want just anyone from anywhere to be able to reach these resources. So we don't want an internet gateway attached to our VPC. Instead, we want a private gateway that only allows people in if they are coming from an approved network, not the public internet. This private doorway is called a virtual private gateway, and it allows you to create a VPN connection between a private network, like your on-premises data center or internal corporate network to your VPC. 


> To relate this back to the coffee shop, this would be like having a private bus route going from my building to the coffee shop. If I want to go get coffee, I first must badge into the building, thus authenticating my identity, and then I can take the secret bus route to the internal coffee shop that only people from my building can use. So if you want to establish an encrypted VPN connection to your private internal AWS resources, you would need to attach a virtual private gateway to your VPC. 


> Now the problem with our super secret bus route is that it still uses the open road. It's susceptible to traffic jams and slowdowns caused by the rest of the world going about their business. The same thing is true for VPN connections. They are private and they are encrypted, but they still use a regular internet connection that has bandwidth that is being shared by many people using the internet. 


> So what I've done to make things more reliable and less susceptible to slowdowns is I made a totally separate magic doorway that leads directly from the studio into the coffee shop. No one else driving around on the road can slow me down because this is my direct doorway; no one else can use it. What, did you not have a secret magic doorway into your favorite coffee shop? All right, moving on. The point being is you still want a private connection, but you want it to be dedicated and shared with no one else. You want the lowest amount of latency possible with the highest amount of security possible. 


> With AWS, you can achieve that using what is called AWS Direct Connect. Direct Connect allows you to establish a completely private, dedicated fiber connection from your data center to AWS. You work with a Direct Connect partner in your area to establish this connection, because like my magic doorway, AWS Direct Connect provides a physical line that connects your network to your AWS VPC. This can help you meet high regulatory and compliance needs, as well as sidestep any potential bandwidth issues. It's also important to note that one VPC might have multiple types of gateways attached for multiple types of resources all residing in the same VPC, just in different subnets. 


> Thanks for listening. I'm gonna sit here and keep ordering coffees from my magic door. See ya.

### Amazon Virtual Private Cloud (Amazon VPC)

Imagine the millions of customers who use AWS services. Also, imagine the millions of resources that these customers have created, such as Amazon EC2 instances. Without boundaries around all of these resources, network traffic would be able to flow between them unrestricted. 

A networking service that you can use to establish boundaries around your AWS resources is [Amazon Virtual Private Cloud (Amazon VPC)](https://aws.amazon.com/vpc/).

> 保護和監控連線、屏蔽流量和限制虛擬網路內的執行個體存取權。
> 
> 花更少時間在設定、管理和驗證您的虛擬網路方面。
> 
> 透過選擇自己的 IP 地址範圍、建立子網路和設定路由表，來自訂您的虛擬網路。
> 
> Amazon Virtual Private Cloud (Amazon VPC) 可讓您完全控制虛擬聯網環境，包括資源置放、連線和安全。透過在 AWS 服務主控台中設定 VPC 開始使用。接著，新增資源至其中，例如 Amazon Elastic Compute Cloud (EC2) 和 Amazon Relational Database Service (RDS) 執行個體。最後，定義 VPC 如何相互、跨帳戶、可用區域或 AWS 區域通訊。在下列範例中，網路流量在每個區域內的兩個 VPC 之間共享。 
> 
> ![](https://i.imgur.com/v9t4G6s.png)

Amazon VPC enables you to provision an isolated section of the AWS Cloud. In this isolated section, you can launch resources in a virtual network that you define. Within a virtual private cloud (VPC), you can organize your resources into subnets. A subnet is a section of a VPC that can contain resources such as Amazon EC2 instances.

### Internet gateway

To allow public traffic from the internet to access your VPC, you attach an internet gateway to the VPC.

> 一個 VPC 如果要讓外部的服務可以訪問，可以透過 VPC dashboard 裡面的 Internet Gateway 設定。所以 Internet Gateways 主要符合 SNAT internet gateway 的網關名稱前綴都會是：igw-*
> 
> Internet gateway 具有可橫向拓展及支持高度可用，可以確保 VPC 與 instance 高可用性，不會受到頻寬及網路流量的限制。

<div align="center">
<img src=https://i.imgur.com/XBSpAJv.png width=80%>
</div>


An internet gateway is a connection between a VPC and the internet. You can think of an internet gateway as being similar to a doorway that customers use to enter the coffee shop. Without an internet gateway, no one can access the resources within your VPC.

### Virtual private gateway

To access private resources in a VPC, you can use a virtual private gateway. 

Here’s an example of how a virtual private gateway works. You can think of the internet as the road between your home and the coffee shop. Suppose that you are traveling on this road with a bodyguard to protect you. You are still using the same road as other customers, but with an extra layer of protection. 

The bodyguard is like a virtual private network (VPN) connection that encrypts (or protects) your internet traffic from all the other requests around it. 

The virtual private gateway is the component that allows protected internet traffic to enter into the VPC. Even though your connection to the coffee shop has extra protection, traffic jams are possible because you’re using the same road as other customers.

> 要訪問 VPC 中的私有資源，您可以使用虛擬私有網關。
> 
> 這是一個虛擬私有網關如何工作的示例。您可以將互聯網視為您的家和咖啡店之間的道路。假設你在這條路上旅行，有保鏢保護你。您仍然使用與其他客戶相同的道路，但有額外的保護層。
> 保鏢就像一個虛擬專用網絡 (VPN) 連接，可以加密（或保護）您的互聯網流量，使其免受周圍所有其他請求的影響。
> 
> 虛擬私有網關是允許受保護的互聯網流量進入 VPC 的組件。即使您與咖啡店的連接有額外的保護，交通擁堵也可能發生，因為您與其他顧客使用同一條道路。 

<div align="center">
<img src=https://i.imgur.com/V4NqFQP.png width=80%>
</div>


**AWS Direct Connect**

<div align="center">
<img src=https://i.imgur.com/l0ADJV1.png width=80%>
</div>


[AWS Direct Connect](https://aws.amazon.com/directconnect/) is a service that enables you to establish a dedicated private connection between your data center and a VPC.  

Suppose that there is an apartment building with a hallway directly linking the building to the coffee shop. Only the residents of the apartment building can travel through this hallway. 

This private hallway provides the same type of dedicated connection as AWS Direct Connect. Residents are able to get into the coffee shop without needing to use the public road shared with other customers. 

> AWS Direct Connect 雲端服務是您 AWS 資源的最短路徑。在傳輸過程中，您的網路流量保留在 AWS 全球網路上，永遠不會接觸公共網際網路。這減少了遇到瓶頸或延遲意外增加的機會。建立新的連線時，您可以選擇 AWS Direct Connect 交付合作夥伴提供的託管連線，或選擇來自 AWS 的專用連線，並在全球 100 多個 AWS Direct Connect 位置進行部署。藉由 AWS Direct Connect SiteLink，您可以在 AWS Direct Connect 位置之間傳送資料，以在全球網路中的辦公室和資料中心之間建立私有網路連線。 
> 
> 
> 
> <div align="center">
> <img src=https://i.imgur.com/2qIs6bE.png width=80%>
> </div>


## Subnets and network access control lists

**Video transcript**

> Welcome to your VPC. You can think of it as a hardened fortress where nothing goes in or out without explicit permission. You have a gateway on the VPC that only permits traffic in or out of the VPC. But that only covers perimeter, and that's only one part of network security that you should be focusing on as part of your IT strategy. 


> AWS has a wide range of tools that cover every layer of security: network hardening, application security, user identity, authentication and authorization, distributed denial-of-service or DDoS prevention, data integrity, encryption, much more. We're gonna talk about a few of these key pieces. And if you really wanna know more about security, please follow the links in this page to be directed to more information and additional training on how to lock your infrastructure down tighter than Aunt Robin's secret lemon pie recipe, and ain't nobody getting that recipe. 

> Today, I wanna talk about a few aspects of network hardening looking at what happens inside the VPC. Now, the only technical reason to use subnets in a VPC is to control access to the gateways. The public subnets have access to the internet gateway; the private subnets do not. But subnets can also control traffic permissions. Packets are messages from the internet, and every packet that crosses the subnet boundaries gets checked against something called a network access control list or network ACL. This check is to see if the packet has permissions to either leave or enter the subnet based on who it was sent from and how it's trying to communicate. 


> You can think of network ACLs as passport control officers. If you're on the approved list, you get through. If you're not on the list, or if you're explicitly on the do-not-enter list, then you get blocked. Network ACLs check traffic going into and leaving a subnet, just like passport control. The list gets checked on your way into a country and on the way out. And just because you were let in doesn't necessarily mean they're gonna let you out. Approved traffic can be sent on its way, and potentially harmful traffic, like attempts to gain control of a system through administrative requests, they get blocked before they ever touch the target. You can't hack what you can't touch. 


> Now, this sounds like great security, but it doesn't answer all of the network control issues. Because a network ACL only gets to evaluate a packet if it crosses a subnet boundary, in or out. It doesn't evaluate if a packet can reach a specific EC2 instance or not. Sometimes, you'll have multiple EC2 instances in the same subnet, but they might have different rules around who can send them messages, what port those messages are allowed to be sent to. So you need instance level network security as well. 


> To solve instance level access questions, we introduce security groups. Every EC2 instance, when it's launched, automatically comes with a security group. And by default, the security group does not allow any traffic into the instance at all. All ports are blocked; all IP addresses sending packets are blocked. That's very secure, but perhaps not very useful. If you want an instance to actually accept traffic from the outside, like say, a message from a front end instance or a message from the Internet. So obviously, you can modify the security group to accept a specific type of traffic. In the case of a website, you want web-based traffic or HTTPS to be accepted but not other types of traffic, say an operating system or administration requests. 


> If NACLs are a passport control, a security group is like the doorman at your building, the building being the EC2 Instance, in this case. The doorman will check a list to ensure that someone is allowed to enter the building but won't bother check the list on the way out. With security groups, you allow specific traffic in and by default, all traffic is allowed out. Now, wait a minute, Blaine. You just described two different engines each doing the exact same job. Let good packets in, keep bad packets out. The key difference between a security group and a network ACL is the security group is stateful, meaning, as we talked about, it has some kind of a memory when it comes to who to allow in or out, and the network ACL is stateless, which remembers nothing and checks every single packet that crosses its border regardless of any circumstances. 


> You know, this metaphor is important to understand. So I wanna illustrate the round trip of a packet as it goes from one instance to another instance in a different subnet. Now, this traffic management, it doesn't care about the contents of the packet itself. In fact, it doesn't even open the envelope, it can't. All it can do is check to see if the sender is on the approved list. 

> All right. Let's start with instance A. We wanna send a packet from instance A to instance B in a different subnet, same VPC, different subnets. So instance A sends the packet. Now, the first thing that happens is that packet meets the boundary of the security group of instance A. By default, all outbound traffic is allowed from a security group. So you can walk right by the doormen and leave, cool, right. The packet made it past the security group of instance A. Now it has to leave the subnet boundary. At the boundary, the passport must now make it through passport control, the network ACL. The network ACL doesn't care about what the security group allowed. It has its own list of who can pass and who can't. If the target address is allowed, you can keep going on your journey, which it is. 


> So now we have exited the original subnet and now the packet goes to the target subnet where instance B lives. Now at this target subnet, once again, we have passport control. Just because the packet was allowed out of its home country does not mean that it can enter the destination country or subnet in this case. They both have unique passport officers with their own checklists. You have to be approved on both lists, or you could get turned away at the border. Well, turns out the packet is on the approved list for this subnet, so it's allowed to enter through the network ACL into the subnet. Almost there. Now, we're approaching the target instance, instance B. Every EC2 Instance has their own security group. You wanna enter this instance, the doorman will need to check to see if you're allowed in, and we're on the list. The packet has reached the target instance. 


> Once the transaction's complete, now it's just time to come home. It's the return traffic pattern. It's the most interesting, because this is where the stateful versus stateless nature of the different engines come into play. Because the packet still has to be evaluated at each checkpoint. Security groups, by default, allow all return traffic. So they don't have to check a list to see if they're allowed out. Instead, they automatically allow the return traffic to pass by no matter what. Passport control here at the subnet boundary, these network ACLs do not remember state. They don't care that the packet came in here. It might be on a you-can't-leave list. Every ingress and egress is checked with the appropriate list. The package return address has to be on their approved list to make it across the border. Made it to the border of the origin subnet, but we have to negotiate passport network ACL control here as well. Stateless controls, means it always checks its list. 


> The packet pass the network ACL, the subnet level, which means the packets now made it back to instance A but the security group, the doorman is still in charge here. The key difference though is these security groups are stateful. The security group recognizes the packet from before. So it doesn't need to check to see if it's allowed in. Come on home. 


> Now, this may seem like we spent a lot of effort just getting a packet from one instance to another and back. You might be concerned about all the network overhead this might generate. The reality is all of these exchanges happen instantly as part of how AWS Networking actually works. If you wanna know the technology that makes all that possible, well, then you need to sign up for a completely different set of trainings. Good network security will take advantage of both network ACLs and security groups, because security in-depth is critical for modern architectures.


To learn more about the role of subnets within a VPC, review the following example from the coffee shop.

First, customers give their orders to the cashier. The cashier then passes the orders to the barista. This process allows the line to keep running smoothly as more customers come in. 

Suppose that some customers try to skip the cashier line and give their orders directly to the barista. This disrupts the flow of traffic and results in customers accessing a part of the coffee shop that is restricted to them.

<div align="center">
<img src=https://i.imgur.com/2SeP5wS.png width=50%>
</div>


To fix this, the owners of the coffee shop divide the counter area by placing the cashier and the barista in separate workstations. The cashier’s workstation is public facing and designed to receive customers. The barista’s area is private. The barista can still receive orders from the cashier but not directly from customers.

<div align="center">
<img src=https://i.imgur.com/3IFcxU9.png width=50%>
</div>


This is similar to how you can use AWS networking services to isolate resources and determine exactly how network traffic flows.

In the coffee shop, you can think of the counter area as a VPC. The counter area divides into two separate areas for the cashier’s workstation and the barista’s workstation. In a VPC, subnets are separate areas that are used to group together resources.

### Subnets

A subnet is a section of a VPC in which you can group resources based on security or operational needs. Subnets can be public or private. 


<div align="center">
<img src=https://i.imgur.com/vdHIOXv.png width=50%>
</div>


Architecture diagram of a VPC with three Amazon EC2 instances in a public subnet and three databases in a private subnet

**Public subnets** contain resources that need to be accessible by the public, such as an online store’s website.

**Private subnets** contain resources that should be accessible only through your private network, such as a database that contains customers’ personal information and order histories. 

In a VPC, subnets can communicate with each other. For example, you might have an application that involves Amazon EC2 instances in a public subnet communicating with databases that are located in a private subnet.

### Network traffic in a VPC

When a customer requests data from an application hosted in the AWS Cloud, this request is sent as a packet. A packet is a unit of data sent over the internet or a network. 

It enters into a VPC through an internet gateway. Before a packet can enter into a subnet or exit from a subnet, it checks for permissions. These permissions indicate who sent the packet and how the packet is trying to communicate with the resources in a subnet.

The VPC component that checks packet permissions for subnets is a [network access control list (ACL)](https://docs.aws.amazon.com/vpc/latest/userguide/vpc-network-acls.html).

### Network access control lists (ACLs)

**A network access control list (ACL) is a virtual firewall** that controls inbound and outbound traffic at the subnet level.

**note**:

> 網路存取控制清單 (ACL) 是 VPC 中的選用安全層，作用就像防火牆，可控制一或多個子網路的傳入和傳出流量。您可以使用與您的安全群組相似的規則來設定網路 ACL，以為您的 VPC 新增額外的安全 layer。如需安全群組與網路 ACL 間差異的詳細資訊，請參閱[比較安全群組和網路 ACL](https://docs.aws.amazon.com/zh_tw/vpc/latest/userguide/VPC_Security.html#VPC_Security_Comparison)。
> 
> <div align="center"><img src=https://i.imgur.com/waA1Yoz.png width=90%></div>
> 


For example, step outside of the coffee shop and imagine that you are in an airport. In the airport, travelers are trying to enter into a different country. You can think of the travelers as packets and the passport control officer as a network ACL. The passport control officer checks travelers’ credentials when they are both entering and exiting out of the country. If a traveler is on an approved list, they are able to get through. However, if they are not on the approved list or are explicitly on a list of banned travelers, they cannot come in.

<div align="center"><img src=https://i.imgur.com/HrFKiEW.png width=50%></div>


Each AWS account includes a default network ACL. When configuring your VPC, you can use your account’s default network ACL or create custom network ACLs. 

By default, your account’s default network ACL allows all inbound and outbound traffic, but you can modify it by adding your own rules. For custom network ACLs, all inbound and outbound traffic is denied until you add rules to specify which traffic to allow. Additionally, all network ACLs have an explicit deny rule. This rule ensures that if a packet doesn’t match any of the other rules on the list, the packet is denied. 

### Stateless packet filtering

Network ACLs perform stateless packet filtering. They remember nothing and check packets that cross the subnet border each way: inbound and outbound. 

Recall the previous example of a traveler who wants to enter into a different country. This is similar to sending a request out from an Amazon EC2 instance and to the internet.

When a packet response for that request comes back to the subnet, the network ACL does not remember your previous request. The network ACL checks the packet response against its list of rules to determine whether to allow or deny.

<div align="center"><img src=https://i.imgur.com/KSI3Krz.png width=80%></div>


After a packet has entered a subnet, it must have its permissions evaluated for resources within the subnet, such as Amazon EC2 instances. 

The VPC component that checks packet permissions for an Amazon EC2 instance is a [security group](https://docs.aws.amazon.com/vpc/latest/userguide/VPC_SecurityGroups.html).

### Security groups

A security group is a virtual firewall that controls inbound and outbound traffic for an Amazon EC2 instance.

<div align="center"><img src=https://i.imgur.com/MMmHh7p.png width=30%></div>


By default, a security group denies all inbound traffic and allows all outbound traffic. You can add custom rules to configure which traffic to allow or deny.

For this example, suppose that you are in an apartment building with a door attendant who greets guests in the lobby. You can think of the guests as packets and the door attendant as a security group. As guests arrive, the door attendant checks a list to ensure they can enter the building. However, the door attendant does not check the list again when guests are exiting the building

If you have multiple Amazon EC2 instances within a subnet, you can associate them with the same security group or use different security groups for each instance. 

### Stateful packet filtering

Security groups perform stateful packet filtering. They remember previous decisions made for incoming packets.

Consider the same example of sending a request out from an Amazon EC2 instance to the internet. 

When a packet response for that request returns to the instance, the security group remembers your previous request. The security group allows the response to proceed, regardless of inbound security group rules.

>安全組執行有狀態數據包過濾。他們記得以前為傳入數據包所做的決定。
>
>考慮從 Amazon EC2 實例向 Internet 發送請求的相同示例。
>
>當該請求的數據包響應返回到實例時，安全組會記住您之前的請求。無論入站安全組規則如何，安全組都允許響應繼續進行。
>

<div align="center"><img src=https://i.imgur.com/Dq5cki6.png width=70%></div>


Both network ACLs and security groups enable you to configure custom rules for the traffic in your VPC. As you continue to learn more about AWS security and networking, make sure to understand the differences between network ACLs and security groups.

![](https://i.imgur.com/Byl3n8f.png)

### Knowledge check

1. In the following, match each part of the application to the correct VPC component.


Isolate databases containing customers' personal information.
==> Private subnet

Create a VPN connection between the VPC and the internal corporate network.
==> Virtual private gateway

Support the customer-facing website. Establish a dedicated connection between the on-premises data center and the VPC.
==> Public subnet

Establish a dedicated connection between the on-premises data center and the VPC.
==> AWS Direct Connect

2. Which statement best describes an AWS account’s default network access control list?

[ ] It is stateless and denies all inbound and outbound traffic.

[ ] It is stateful and allows all inbound and outbound traffic.

[ ] It is stateless and allows all inbound and outbound traffic.

[ ] It is stateful and denies all inbound and outbound traffic.

>By default, your account’s default network ACL allows all inbound and outbound traffic, but you can modify it by adding your own rules. For custom network ACLs, all inbound and outbound traffic is denied until you add rules to specify which traffic should be allowed. Additionally, all network ACLs have an explicit deny rule. This rule ensures that if a packet doesn’t match any of the other rules on the list, the packet is denied.
>

## Global networking

**Video transcript**

> We've been talking a lot about how you interact with your AWS infrastructure. But how do your customers interact with your AWS infrastructure? Well, if you have a website hosted at AWS, then customers usually enter your website into their browser, hit Enter, some magic happens, and the site opens up. 

> But how does this magic work? Well, just like this magic coin that I have here, you know, you take a bite, and it's, it's back. Well, not quite like that, but I'm going to take you through two services, which would help in the website case. The first one being Route 53. Route 53 is AWS's domain name service, or DNS, and it's highly available and scalable. But wait, what is DNS, you say? Think of DNS as a translation service. But instead of translating between languages, it translates website names into IP, or Internet Protocol, addresses that computers can read. 

> For example, when we enter a website address into our browser, it contacts Route 53 to obtain the IP address of the site, say, 192.1.1.1, then it routes your computer or browser to that address. If we go further, Route 53 can direct traffic to different endpoints using several different routing policies, such as latency-based routing, geolocation DNS, geoproximity, and weighted round robin. If we take geolocation DNS, that means we direct traffic based on where the customer is located. So traffic coming from say North America is routed to the Oregon Region, and traffic in Ireland is routed to the Dublin Region, as an example. 

> You can even use Route 53 to register domain names, so you can buy and manage your own domain names right on AWS. 

> Speaking of websites, there is another service which can help speed up delivery of website assets to customers, Amazon CloudFront. If you remember, we talked about Edge locations earlier in the course, these locations are serving content as close to customers as possible, and one part of that, is the content delivery network, or CDN. For those who need reminding, a CDN is a network that helps to deliver edge content to users based on their geographic location. 

> If we go back to our North America versus Ireland example, say we have a user in Seattle, and they want to access a website, to speed this up, we host the site in Oregon, and we deploy our static web assets, like images and GIFs in CloudFront in North America. This means they get content delivered as close to them as possible, North America in this case, when they access the site. But for our Irish users, it doesn't make sense to deliver those assets out of Oregon, as the latency is not favorable. Thus we deploy those same static assets in CloudFront, but this time in the Dublin Region. That means they can access the same content, but from a location closer to them, which in turn improves latency. 

> I hope you're content after learning about these two services. Thanks for following along, and I'm going to disappear just like this red cloth. Tada!


### Domain Name System (DNS)

Suppose that AnyCompany has a website hosted in the AWS Cloud. Customers enter the web address into their browser, and they are able to access the website. This happens because of Domain Name System (DNS) resolution. DNS resolution involves a customer DNS resolver communicating with a company DNS server.

You can think of DNS as being the phone book of the internet. DNS resolution is the process of translating a domain name to an IP address. 

<div align="center"><img src=https://i.imgur.com/gGdghNK.png width=80%></div>


For example, suppose that you want to visit AnyCompany’s website. 

1. When you enter the domain name into your browser, this request is sent to a customer DNS resolver. 
2. The customer DNS resolver asks the company DNS server for the IP address that corresponds to AnyCompany’s website.
3. The company DNS server responds by providing the IP address for AnyCompany’s website, 192.0.2.0.

### Amazon Route 53

Amazon Route 53 is a DNS web service. It gives developers and businesses a reliable way to route end users to internet applications hosted in AWS. 

Amazon Route 53 connects user requests to infrastructure running in AWS (such as Amazon EC2 instances and load balancers). It can route users to infrastructure outside of AWS.

Another feature of Route 53 is the ability to manage the DNS records for domain names. You can register new domain names directly in Route 53. You can also transfer DNS records for existing domain names managed by other domain registrars. This enables you to manage all of your domain names within a single location.

In the previous module, you learned about Amazon CloudFront, a content delivery service. The following example describes how Route 53 and Amazon CloudFront work together to deliver content to customers.

**Example: How Amazon Route 53 and Amazon CloudFront deliver content**

<div align="center"><img src=https://i.imgur.com/z8sUTG3.png width=80%></div>

Suppose that AnyCompany’s application is running on several Amazon EC2 instances. These instances are in an Auto Scaling group that attaches to an Application Load Balancer. 

1. A customer requests data from the application by going to AnyCompany’s website. 
2. Amazon Route 53 uses DNS resolution to identify AnyCompany.com’s corresponding IP address, 192.0.2.0. This information is sent back to the customer. 
3. The customer’s request is sent to the nearest edge location through Amazon CloudFront. 
4. Amazon CloudFront connects to the Application Load Balancer, which sends the incoming packet to an Amazon EC2 instance.

### Knowledge check

1. Which statement best describes DNS resolution?

[ ] Launching resources in a virtual network that you define

[ ] Storing local copies of content at edge locations around the world

[ ] Connecting a VPC to the internet

[ ] Translating a domain name to an IP address

## Module 4 summary

In Module 4, you learned about the following concepts:

* Structuring and connecting to a VPC
* Securing VPC resources with network access control lists and security groups
* Using Amazon Route 53 and Amazon CloudFront to deliver content

**Video transcript**

> Networking used to be the exclusive domain of topological geniuses. With AWS, networking is now simplified and abstracted to answer the simple question of who should be allowed to communicate with each other. As long as you can answer that question, then you can set up your network on AWS. 


> We covered the basics of VPC, the virtual private cloud, the way that you isolate your workload in AWS, the fundamentals of network security, including gateways, network ACLs, and security groups, all methods that allow your security engineers to craft a network that allows healthy traffic access while dropping subversive attacks before they reach your instance, ways to connect to AWS through VPN and even Direct Connect, secure pipelines that are either encrypted over the general internet or exclusive fiber used by you and you alone. 


> We also talked about the global networks that AWS provides using our Edge locations, how you can use Route 53 for DNS, and how to use CloudFront to cache content closer to your actual consumers. 


> So while this only scratches the surface of the many things you can do with AWS networking, we hope that it gives you an understanding of the key moving pieces you need to get your business started.

### Additional resources

To learn more about the concepts that were explored in Module 4, review these resources.

[Networking and Content Delivery on AWS](https://aws.amazon.com/tw/products/networking/)
[AWS Networking & Content Delivery Blog](https://aws.amazon.com/tw/blogs/networking-and-content-delivery/)
[Amazon Virtual Private Cloud](https://aws.amazon.com/tw/vpc/)
[What is Amazon VPC?](https://docs.aws.amazon.com/vpc/latest/userguide/what-is-amazon-vpc.html)
[How Amazon VPC works](https://docs.aws.amazon.com/vpc/latest/userguide/how-it-works.html)

## Module 4 quiz

Test your knowledge of some of the key concepts from this module by answering the questions in this quiz.

1. Your company has an application that uses Amazon EC2 instances to run the customer-facing website and Amazon RDS database instances to store customers’ personal information. How should the developer configure the VPC according to best practices?

[ ] Place the Amazon EC2 instances in a private subnet and the Amazon RDS database instances in a public subnet.

[ ] Place the Amazon EC2 instances in a public subnet and the Amazon RDS database instances in a private subnet.

[ ] Place the Amazon EC2 instances and the Amazon RDS database instances in a public subnet.

[ ] Place the Amazon EC2 instances and the Amazon RDS database instances in a private subnet.

2. Which component or service can be used to establish a private dedicated connection between your company’s data center and AWS?

[ ] Private subnet

[ ] DNS

[ ] AWS Direct Connect

[ ] Amazon CloudFront

3. Which statement best describes security groups?

[ ] They are stateful and deny all inbound traffic by default.

[ ] They are stateful and allow all inbound traffic by default.

[ ] They are stateless and deny all inbound traffic by default.

[ ] They are stateless and allow all inbound traffic by default.

3. Which component is used to connect a VPC to the internet?

[ ] Public subnet

[ ] Edge location

[ ] Security group

[*] Internet gateway


4. Which service is used to manage the DNS records for domain names?

[ ] Amazon Virtual Private Cloud

[ ] AWS Direct Connect

[ ] Amazon CloudFront

[ ] Amazon Route 53

# Module 5: Storage and Databases

## Module 5 introduction

### Learning objectives

In this module, you will learn how to:

* Summarize the basic concept of storage and databases.
* Describe the benefits of Amazon Elastic Block Store (Amazon EBS).
* Describe the benefits of Amazon Simple Storage Service (Amazon S3).
* Describe the benefits of Amazon Elastic File System (Amazon EFS).
* Summarize various storage solutions.
* Describe the benefits of Amazon Relational Database Service (Amazon RDS).
* Describe the benefits of Amazon DynamoDB.
* Summarize various database services.

**Video transcript**

> Well, we have quite a coffee operation going now. We've got customers, lots of happy customers. In fact, we have an elastic, scalable, disaster resistant, cost optimized architecture that now has a global, highly secured network that can be deployed entirely programmatically.

> You know, now we need some way to show our appreciation to all our loyal customers. How about a frequent drinker loyalty program? Or we could just hand out punch cards, but let's be honest, we can't track those well and use them to get to know our customers better. 


> We need digital cards, which means we need to be able to keep track of our customers, what they order, how much they purchased. This will help them, the customers, get the best rewards they've earned and help us to know our customer base better. 


> This means we need databases. Databases, and storage. And not just any database. We need to make sure we choose the right database for the task and the right storage for data types.

> Now you may have many different data usage needs and data types. Let's learn about the different services AWS has to help you build the perfect data solution.

## Instance stores and Amazon Elastic Block Store (Amazon EBS)

**Video transcript**

> When you're using Amazon EC2 to run your business applications, those applications need access to CPU, memory, network, and storage. EC2 instances give you access to all those different components, and right now, let's focus on the storage access. As applications run, they will oftentimes need access to block-level storage. 


> You can think of block-level storage as a place to store files. A file being a series of bytes that are stored in blocks on disc. When a file is updated, the whole series of blocks aren't all overwritten. Instead, it updates just the pieces that change. This makes it an efficient storage type when working with applications like databases, enterprise software, or file systems. 


> When you use your laptop or personal computer, you are accessing block-level storage. All block-level storage is in this case is your hard drive. EC2 instances have hard drives as well. And there are a few different types. 


> When you launch an EC2 instance, depending on the type of the EC2 instance you launched, it might provide you with local storage called instance store volumes. These volumes are physically attached to the host, your EC2 instances running on top of. And you can write to it just like a normal hard drive. The catch here is that since this volume is attached to the underlying physical host, if you stop or terminate your EC2 instance, all data written to the instance store volume will be deleted. The reason for this, is that if you start your instance from a stop state, it's likely that EC2 instance will start up on another host. A host where that volume does not exist. Remember EC2 instances are virtual machines, and therefore the underlying host can change between stopping and starting an instance. 


> Because of this ephemeral or temporary nature of instance store volumes, they are useful in situations where you can lose the data being written to the drive. Such as temporary files, scratch data, and data that can be easily recreated without consequence.

 

> All right, I'm telling you not to write important data to the drives that come with EC2 instances. I'm sure that sounds a bit scary because obviously you'll need a place to write data that persists outside of the life cycle of an EC2 instance. You don't want your entire database getting deleted every time you stop an EC2 instance. Don't worry, this is where a service called Amazon Elastic Block Store, or EBS, comes into play. 


> With EBS, you can create virtual hard drives, that we call EBS volumes, that you can attach to your EC2 instances. These are separate drives from the local instance store volumes, and they aren't tied directly to the host that your EC2 is running on. This means, that the data that you write to an EBS volume can persists between stops and starts of an EC2 instance. 


> EBS volumes come in all different sizes and types. How this works, is you define the size, type and configurations of the volume you need. Provision the volume, and then attach it to your EC2 instance. From there, you can configure your application to write to the volume and you're good to go. If you stop and then start the EC2 instance, the data in the volume remains. 


> Since the use case for EBS volumes is to have a hard drive that is persistent, that your applications can write to, it's probably important that you back that data up. EBS allows you to take incremental backups of your data called snapshots. It's very important that you take regular snapshots of your EBS volumes This way, if a drive ever becomes corrupted, you haven't lost your data. And you can restore that data from a snapshot.
> 

### Instance stores

Block-level storage volumes behave like physical hard drives.

An instance store provides temporary block-level storage for an Amazon EC2 instance. An instance store is disk storage that is physically attached to the host computer for an EC2 instance, and therefore has the same lifespan as the instance. When the instance is terminated, you lose any data in the instance store.

Step 1: An Amazon EC2 instance with an attached instance store is running.

<div align="center"><img src=https://i.imgur.com/6AA00IX.png width=20%></div>

Step 2: The instance is stopped or terminated.

<div align="center"><img src=https://i.imgur.com/OfXI2tE.png width=20%></div>

Step 3: All data on the attached instance store is deleted.

<div align="center"><img src=https://i.imgur.com/fysIIw0.png width=20%></div>

[Amazon Elastic Block Store (Amazon EBS)](https://aws.amazon.com/ebs) is a service that provides block-level storage volumes that you can use with Amazon EC2 instances. If you stop or terminate an Amazon EC2 instance, all the data on the attached EBS volume remains available.

To create an EBS volume, you define the configuration (such as volume size and type) and provision it. After you create an EBS volume, it can attach to an Amazon EC2 instance.

<div align="center"><img src=https://i.imgur.com/Bra2Jos.png width=30%></div>

Because EBS volumes are for data that needs to persist, it’s important to back up the data. You can take incremental backups of EBS volumes by creating Amazon EBS snapshots.

>   Amazon Elastic Block Store (Amazon EBS) 是易於使用、可擴展的高效能區塊儲存服務，專為與 Amazon Elastic Compute Cloud (Amazon EC2) 搭配使用而設計。 
> 
> <div align="center"><img src=https://i.imgur.com/yG7BJYc.png width=100%></div>

### Amazon EBS snapshots

<div align="center"><img src=https://i.imgur.com/0vIO1nq.png width=80%></div>

An [EBS snapshot](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/EBSSnapshots.html) is an incremental backup. This means that the first backup taken of a volume copies all the data. For subsequent backups, only the blocks of data that have changed since the most recent snapshot are saved. 

Incremental backups are different from full backups, in which all the data in a storage volume copies each time a backup occurs. The full backup includes data that has not changed since the most recent backup.

## Amazon Simple Storage Service (Amazon S3)

**Video transcript**

> Welcome to this video on Amazon Simple Storage Service, or S3. From the name, you've probably guessed that it is a storage service and it's, well, simple. Most businesses have data that needs to be stored somewhere. For the coffee shop, this could be receipts, images, Excel spreadsheets, employee training videos, and even text files, among others. Storing these files is where S3 comes in handy because it is a data store that allows you to store and retrieve an unlimited amount of data at any scale. 


> Data is stored as objects, but instead of storing them in a file directory, you store them in what we call buckets. Think of a file sitting on your hard drive, that is an object and think of a file directory, that is the bucket. The maximum object size that you can upload is five terabytes. You can also version objects to protect them from accidental deletion of an object. What this means is that you always retain the previous versions of an object, as like a paper trail. You can even create multiple buckets and store them across different classes or tiers of data. You can then create permissions to limit who can see or even access objects. 


> And you can even stage data between different tiers. These tiers offer mechanisms for different storage use cases such as data that needs to be accessed frequently, versus audit data that needs to be retained for several years. Let's go through the notable ones, shall we? 


> The first here is called S3 Standard and comes with 11 nines of durability. That means an object stored in S3 Standard has a 99.999999999 percentage – that's a lot of nines –  probability that it will remain intact after a period of one year. That's pretty high. Furthermore, data is stored in such a way that AWS can sustain the concurrent loss of data in two separate storage facilities. This is because data is stored in at least three facilities. So multiple copies reside across locations. Another useful way to use S3 is static website hosting, where a static website is a collection of HTML files and each file is akin to a physical page of the actual site. You can do this by simply uploading all your HTML, static web assets, and so forth into a bucket and then checking a box to host it as a static website. You can then enter the bucket's URL and ba-bam! Instant website. And we say static, but that doesn't mean you can't have animations and moving parts to your website. Pretty awesome way to start up that coffee blog. 


> The next storage class is called S3 Infrequent Access or S3-IA. Which is used for data that is accessed less frequently but requires rapid access when needed. This means it's a perfect place to store backups, disaster recovery files, or any object that requires a long-term storage. 


> Another storage class or tier lends itself to that example we had earlier about audit data. Say, we need to retain data for several years for auditing purposes. And we don't need it to be retrieved very rapidly. Well, then you can use Amazon S3 Glacier to archive that data. To use Glacier, you can simply move data to it, or you can create vaults and then populate them with archives. And if you have compliance requirements around retaining data for, say, a certain period of time, you can employ an S3 Glacier vault lock policy and lock your vault. You can specify controls such as write once/ read many, or WORM, in a vault lock policy and lock the policy from future edits. Once locked, the policy can no longer be changed. You also have three options for retrieval, which range from minutes to hours, and you have the option of uploading directly to Glacier or using S3 Lifecycle policies. 


> Fact, I don't think we mentioned lifecycle policies up till this point. But they are policies you can create that can move data automatically between tiers. For example, say we need to keep an object in S3 Standard for 90 days, and then we want to move it to S3-IA for the next 30 days. Then after 120 days total, we want it to be moved to S3 Glacier. With Lifecycle policies, you create that configuration without changing your application code and it will perform those moves for you automatically. It's another example of a managed AWS service, helping take that burden off you, so you can focus on more of your business needs. 


> Just to note that there are other storage classes. Like S3 Infrequent Access One Zone and S3 Glacier Deep Archive that you can use. Happy storing.

### Object storage

In object storage, each object consists of data, metadata, and a key.

The data might be an image, video, text document, or any other type of file. Metadata contains information about what the data is, how it is used, the object size, and so on. An object’s key is its unique identifier.

<div align="center"><img src=https://i.imgur.com/fGuRokk.png width=60%></div>

### Amazon Simple Storage Service (Amazon S3)

Amazon Simple Storage Service (Amazon S3) is a service that provides object-level storage. Amazon S3 stores data as objects in buckets.

You can upload any type of file to Amazon S3, such as images, videos, text files, and so on. For example, you might use Amazon S3 to store backup files, media files for a website, or archived documents. Amazon S3 offers unlimited storage space. The maximum file size for an object in Amazon S3 is 5 TB.

When you upload a file to Amazon S3, you can set permissions to control visibility and access to it. You can also use the Amazon S3 versioning feature to track changes to your objects over time.

### Amazon S3 storage classes

With Amazon S3, you pay only for what you use. You can choose from a range of storage classes to select a fit for your business and cost needs. When selecting an Amazon S3 storage class, consider these two factors:

* How often you plan to retrieve your data
* How available you need your data to be

**S3 Standard（S3 標準）**
    
* Designed for frequently accessed data
* Stores data in a minimum of three Availability Zones

S3 Standard provides high availability for objects. This makes it a good choice for a wide range of use cases, such as websites, content distribution, and data analytics. S3 Standard has a higher cost than other storage classes intended for infrequently accessed data and archival storage.

**S3 Standard-Infrequent Access (S3 Standard-IA)（S3 標準-不頻繁訪問（S3 標準-IA））**

* Ideal for infrequently accessed data(非常適合不經常訪問的數據)
* Similar to S3 Standard but has a lower storage price and higher retrieval price(與 S3 Standard 類似，但存儲價格較低，檢索價格較高)

S3 Standard-IA is ideal for data infrequently accessed but requires high availability when needed. Both S3 Standard and S3 Standard-IA store data in a minimum of three Availability Zones. S3 Standard-IA provides the same level of availability as S3 Standard but with a lower storage price and a higher retrieval price.

**S3 One Zone-Infrequent Access (S3 One Zone-IA)（S3 One Zone-不頻繁訪問（S3 One Zone-IA））**

* Stores data in a single Availability Zone
* Has a lower storage price than S3 Standard-IA

Compared to S3 Standard and S3 Standard-IA, which store data in a minimum of three Availability Zones, S3 One Zone-IA stores data in a single Availability Zone. This makes it a good storage class to consider if the following conditions apply:

* You want to save costs on storage.
* You can easily reproduce your data in the event of an Availability Zone failure.

> S3 One Zone-IA 將數據存儲在單個可用區中。如果以下條件適用，這使它成為一個很好的存儲類：
> 
> * 您想節省存儲成本。
> 
> * 如果出現可用區故障，您可以輕鬆地複制數據
> 

**S3 Intelligent-Tiering（S3 智能分層）**

* Ideal for data with unknown or changing access patterns
* Requires a small monthly monitoring and automation fee per object

> * 非常適合具有未知或不斷變化的訪問模式的數據
> 
> * 每個對象需要每月支付少量監控和自動化費用

In the S3 Intelligent-Tiering storage class, Amazon S3 monitors objects’ access patterns. If you haven’t accessed an object for 30 consecutive days, Amazon S3 automatically moves it to the infrequent access tier, S3 Standard-IA. If you access an object in the infrequent access tier, Amazon S3 automatically moves it to the frequent access tier, S3 Standard.

**S3 Glacie（S3冰川）r**

* Low-cost storage designed for data archiving
* Able to retrieve objects within a few minutes to hours

> * 專為數據歸檔而設計的低成本存儲
> 
> * 能夠在幾分鐘到幾小時內檢索對象

S3 Glacier is a low-cost storage class that is ideal for data archiving. For example, you might use this storage class to store archived customer records or older photos and video files.

**S3 Glacier Deep Archive（S3 冰川深度存檔）**

* owest-cost object storage class ideal for archiving
* Able to retrieve objects within 12 hours

> * 成本最低的對象存儲類，非常適合歸檔
> *  能夠在 12 小時內取回物品
> 

When deciding between Amazon S3 Glacier and Amazon S3 Glacier Deep Archive, consider how quickly you need to retrieve archived objects. You can retrieve objects stored in the S3 Glacier storage class within a few minutes to a few hours. By comparison, you can retrieve objects stored in the S3 Glacier Deep Archive storage class within 12 hours.

### Knowledge check

1. You want to store data that is infrequently accessed but must be immediately available when needed. Which Amazon S3 storage class should you use?

[ ] S3 Intelligent-Tiering

[ ] S3 Glacier Deep Archive

[ ] S3 Standard-IA

[ ] S3 Glacier

### Comparing Amazon EBS and Amazon S3

**Video transcript**

> AWS Cloud Practitioners, welcome to the clash of the storage class! In the block storage corner, weighing in at sizes up to 16 tebibytes each, with a unique ability to survive the termination of their Amazon EC2 instances, they are solid state, they are spinning platters, they are Amazon Elastic Block Storage! 


> In the regional object storage corner, weighing in at unlimited storage, with individual objects at 5,000 gigabytes in size, they specialize in write once/read many, they are 99 .999 999 999% durable, they are Amazon Simple Storage Service! 


> Head-to-head, each storage class boasts the best dynamically distributed design for different storage demands. Which storage class will ultimately be victorious in this thunderdome slugfest? To understand who wins, you need to clarify a use case. 


> Round one. Let's say you're running a photo analysis website where users upload a photo of themselves, and your application finds the animals that look just like them. You have potentially millions of animal pictures that all need to be indexed and possibly viewed by thousands of people at once. This is the perfect use case for S3. S3 is already web enabled. Every object already has a URL that you can control access rights to who can see or manage the image. It's regionally distributed, which means that it has 11 nines of durability, so no need to worry about backup strategies. S3 is your backup strategy. Plus the cost savings is substantial overrunning the same storage load on EBS. With the additional advantage of being serverless, no Amazon EC2 instances are needed. Sounds like S3 is the judge's winner here for this round. 


> But wait, round two, you have an 80-gigabyte video file that you're making edit corrections on. To know the best storage class here, we need to understand the difference between object storage and block storage. Object storage treats any file as a complete, discreet object. Now this is great for documents, and images, and video files that get uploaded and consumed as entire objects, but every time there's a change to the object, you must re-upload the entire file. There are no delta updates. Block storage breaks those files down to small component parts or blocks. This means, for that 80-gigabyte file, when you make an edit to one scene in the film and save that change, the engine only updates the blocks where those bits live. If you're making a bunch of micro edits, using EBS, elastic block storage, is the perfect use case. If you were using S3, every time you saved the changes, the system would have to upload all 80 gigabytes, the whole thing, every time. EBS clearly wins round two. 


> This means, if you are using complete objects or only occasional changes, S3 is victorious. If you are doing complex read, write, change functions, then, absolutely, EBS is your knockout winner. Your winner depends on your individual workload. Each service is the right service for specific needs. Once you understand what you need, you will know which service is your champion!
> 

## Amazon Elastic File System (Amazon EFS)

**Video transcript**

> Next up on the list of storage services is Amazon Elastic File System, or what we call EFS. EFS is a managed file system. It's extremely common for businesses to have shared file systems across their applications. For example, you might have multiple servers running analytics on large amounts of data being stored in a shared file system. This data traditionally has been hosted on premises. In this on-premises data center, you would have to ensure that the storage you have can keep up with the amount of data that you are storing. Make sure backups are taken, and that the data is stored redundantly as well as manage all of the servers hosting that data. 


> Luckily with AWS, you don't need to worry about buying all of that hardware and keeping the whole file system running from an operational standpoint. With EFS, you can keep existing file systems in place but let AWS do all the heavy lifting of the scaling and the replication. EFS allows you to have multiple instances accessing the data in EFS at the same time. It scales up and down as needed without you needing to do anything to make that scaling happen. Super nice, right? Well, you might be thinking, Amazon EBS also lets me store files that I can access from EC2 instances. What exactly is the difference here?


> [Blaine] AWS Cloud Practitioners, welcome back!


> [Morgan] All right, we don't need to do all of that. The answer is really simple. Amazon EBS volumes attach to EC2 instances and are an Availability Zone-level resource. In order to attach EC2 to EBS, you need to be in the same AZ. You can save files on it. You can also run a database on top of it. Or store applications on it. It's a hard drive. If you provision a two terabyte EBS volume and fill it up, it doesn't automatically scale to give you more storage. So that's EBS. Amazon EFS can have multiple instances reading and writing from it at the same time.


> But it isn't just a blank hard drive that you can write to. It is a true file system for Linux. It is also a regional resource. Meaning any EC2 instance in the Region can write to the EFS file system. As you write more data to EFS, it automatically scales. No need to provision any more volumes.

### File storage

>  運作方式
> 
> Amazon Elastic File System (Amazon EFS) 會隨您新增和移除檔案時自動增長和縮減，而無需管理或佈建。 
> 
> ![](https://i.imgur.com/NHmh4TV.png)
> 

In file storage, multiple clients (such as users, applications, servers, and so on) can access data that is stored in shared file folders. In this approach, a storage server uses block storage with a local file system to organize files. Clients access data through file paths.

Compared to block storage and object storage, file storage is ideal for use cases in which a large number of services and resources need to access the same data at the same time.

[Amazon Elastic File System (Amazon EFS)](https://aws.amazon.com/efs/) is a scalable file system used with AWS Cloud services and on-premises resources. As you add and remove files, Amazon EFS grows and shrinks automatically. It can scale on demand to petabytes without disrupting applications. 

### Comparing Amazon EBS and Amazon EFS

**Amazon EBS** 

* An Amazon EBS volume stores data in a single Availability Zone. 
* To attach an Amazon EC2 instance to an EBS volume, both the Amazon EC2 instance and the EBS volume must reside within the same Availability Zone.

** Amazon EFS**

* Amazon EFS is a regional service. It stores data in and across multiple Availability Zones. 

* The duplicate storage enables you to access data concurrently from all the Availability Zones in the Region where a file system is located. Additionally, on-premises servers can access Amazon EFS using AWS Direct Connect.

## Amazon Relational Database Service (Amazon RDS)

**Video transcript**

> So you're storing data about your coffee shop in various systems. But you're finding that you need to maintain relationships between various types of data. And by relationships, I mean, if say, a customer orders the same drink multiple times, maybe you want to offer them a promotional discount on their next purchase. And you need a way to keep track of this relationship somewhere. In this case, it's best to use a relational database management system, or RDBMS. Essentially, It means we store data in a way such that it relates to other pieces of data. 


> For example, if we had a customer entry or record, we store that in a customer table. We then could have an entry for the physical address, which we store on a corresponding address table. We then relate the two via a common attribute and can query the data that is housed in both tables. 


> The most common way to query the data is by writing queries in SQL. And this runs on a variety of database systems. Speaking of database systems, what are some of the more well known ones that AWS supports? Well, there's MySQL, PostgreSQL, Oracle, Microsoft SQL Server, and many more. If you have an on-premises environment, you're probably running one of those and they're most likely housed in your data center. 


> But is there a way to easily move them to the cloud? Well, the simple answer is yes, you can do what we call a Lift-and-Shift, and migrate your database to run on Amazon EC2. This means you have control over the same variables you do, in your on-premises environment, such as OS, memory, CPU, storage capacity, and so forth. It's a quick entry to the cloud, and you can migrate them using standard practices or using something like Database Migration Service, which we'll cover in a later video. 


> The other option for running your databases in the cloud is to use a more managed service called Amazon Relational Database Service, or RDS. It supports all the major database engines, like the ones we mentioned earlier, but this service comes with added benefits. These include automated patching, backups, redundancy, failover, disaster recovery, all of which you normally have to manage for yourself. This makes it an extremely attractive option to AWS customers, as it allows you to focus on business problems and not maintaining databases. Which if you're a database admin, can be pretty time consuming and difficult. 


> So how do we make it even easier for you to run database workloads on the cloud? Well, we go one further and have them migrate or deploy to Amazon Aurora. It's our most managed relational database option. It comes in two forms, MySQL and PostgreSQL. And is priced is 1/10th the cost of commercial grade databases. That's a pretty cost effective database. The other benefits are things like your data is replicated across facilities, so you have six copies at any given time. You can also deploy up to 15 read replicas, so you can offload your reads and scale performance. Additionally, there's continuous backups to S3, so you always have a backup ready to restore. You also get point in time recovery, so you can recover data from a specific period. 

> And there you have it, relational databases in a nutshell.

### Relational databases

In a relational database, data is stored in a way that relates it to other pieces of data. 

An example of a relational database might be the coffee shop’s inventory management system. Each record in the database would include data for a single item, such as product name, size, price, and so on.

Relational databases use **structured query language (SQL)** to store and query data. This approach allows data to be stored in an easily understandable, consistent, and scalable way. For example, the coffee shop owners can write a SQL query to identify all the customers whose most frequently purchased drink is a medium latte.

### Amazon Relational Database Service


[Amazon Relational Database Service (Amazon RDS)](https://aws.amazon.com/tw/rds/) is a service that enables you to run relational databases in the AWS Cloud.

>Amazon Relational Database Service (Amazon RDS) 讓使用者能夠在雲端中輕鬆設定、操作和擴展關聯式資料庫。它提供符合成本效益且可調整大小的容量，且可自動處理硬體佈建、資料庫設定、修補程式和備份等耗時的管理任務。這讓您有更多時間專注在應用程式，以提供其所需的快速效能、高可用性、安全性和相容性。
>
>針對記憶體、效能或輸入/輸出進行優化的多種資料庫執行個體類型都提供 Amazon RDS，並可讓您選擇六種熟悉的資料庫引擎，包括 Amazon Aurora、PostgreSQL、MySQL、MariaDB、Oracle Database 和 SQL Server。您可以使用 AWS Database Migration Service 輕鬆地將現有的資料庫遷移或複寫到 Amazon RDS。

Amazon RDS is a managed service that automates tasks such as hardware provisioning, database setup, patching, and backups. With these capabilities, you can spend less time completing administrative tasks and more time using data to innovate your applications. You can integrate Amazon RDS with other services to fulfill your business and operational needs, such as using AWS Lambda to query your database from a serverless application.

Amazon RDS provides a number of different security options. Many Amazon RDS database engines offer encryption at rest (protecting data while it is stored) and encryption in transit (protecting data while it is being sent and received).

### Amazon RDS database engines

Amazon RDS is available on six database engines, which optimize for memory, performance, or input/output (I/O). Supported database engines include:

* Amazon Aurora
* PostgreSQL
* MySQL
* MariaDB
* Oracle Database
* Microsoft SQL Server
    
### Amazon Aurora(亞馬遜極光)

Amazon Aurora is an enterprise-class relational database. It is compatible with MySQL and PostgreSQL relational databases. It is up to five times faster than standard MySQL databases and up to three times faster than standard PostgreSQL databases.

Amazon Aurora helps to reduce your database costs by reducing unnecessary input/output (I/O) operations, while ensuring that your database resources remain reliable and available. 

Consider Amazon Aurora if your workloads require high availability. It replicates six copies of your data across three Availability Zones and continuously backs up your data to Amazon S3.

> Amazon Aurora 是專為雲端建立的 MySQL 和 PostgreSQL 相容關聯式資料庫，結合了傳統企業資料庫的效能和可用性，以及開放原始碼資料庫的簡單與經濟實惠優勢。
> 
> Amazon Aurora 可提供比標準 MySQL 資料庫快五倍的速度，以及比標準 PostgreSQL 資料庫快三倍的速度。它提供商業資料庫的安全性、可用性和可靠性，但只需 1/10 的費用。Amazon Aurora 完全由 Amazon Relational Database Service (RDS) 管理，將硬體佈建、資料庫設定、修補和備份等耗時的管理任務自動化。
> 
> Amazon Aurora 的特色為具有容錯和自我修復能力的分散式儲存系統，每個資料庫執行個體可自動擴展至高達 128 TB。它提供高效能和可用性，以及高達 15 個低延遲僅供讀取複本、point-in-time 恢復、持續備份至 Amazon S3，還可以跨三個可用區域複寫。

### Amazon DynamoDB

**Video transcript**

> Let's talk about Amazon DynamoDB. At its most basic level, DynamoDB is a database. It's a serverless database, meaning you don't need to manage the underlying instances or infrastructure powering it. 


> With DynamoDB, you create tables. A DynamoDB table, is just a place where you can store and query data. Data is organized into items, and items have attributes. Attributes are just different features of your data. If you have one item in your table, or 2 million items in your table, DynamoDB manages the underlying storage for you. And you don't need to worry about the scaling of the system, up or down. 


> DynamoDB stores this data redundantly across availability zones and mirrors the data across multiple drives under the hood for you. This makes the burden of operating a highly available database, much lower. 


> DynamoDB, beyond being massively scalable, is also highly performant. DynamoDB has a millisecond response time. And when you have applications with potentially millions of users, having scalability and reliable lightning fast response times is important. 


> Now, DynamoDB isn't a normal database. In the sense that it doesn't use the very widely used query language, sequel, or SQL. Relational databases, like a standard MySQL Database, require that you have a well defined schema, in place. That might consist of one, or many tables that might relate to each other. You then use SQL to query the data. 


> This works great for a lot of use cases, and has been the standard type of database historically. However, these types of rigid SQL databases, can have performance and scaling issues when under stress. The rigid schema also makes it so that you cannot have any variation in the types of data that you store in a table. So, it might not be the best fit for a dataset that is a little bit less rigid, and is being accessed at a very high rate. 


> This is where non-relational, or NoSQL, databases come in. DynamoDB is a non-relational database. Non-relational databases tend to have simple flexible schemas, not complex rigid schemas, laying out multiple tables that all relate to each other. 


> With DynamoDB, you can add and remove attributes from items in the table, at any time. Not every item in the table has to have the same attributes. This is great for datasets that have some variation from item to item. Because of this flexibility, you cannot run complex SQL queries on it. Instead, you would write queries based on a small subset of attributes that are designated as keys. 


> Because of this, the queries that you run are non-relational databases tend to be simpler, and focus on a collection of items from one table, not queries than span multiple tables. This query pattern, along with other factors, including the way that the underlying system is designed, allows DynamoDB to be very quick in response time, and highly scalable. 


> So, things to remember: DynamoDB is a non-relational, NoSQL database. It is purpose built. Meaning it has specific use cases, and it isn't the best fit for every workload out there. It has millisecond response time. It's fully managed, and it's highly scalable. One awesome example is on Prime Day in 2019, across the 48 hours of Prime Day, there were 7.11 trillion calls to the DynamoDB API, peaking at 45.4 million requests per second. That's insanely scalable, all without the underlying database management. That's pretty cool.

### Nonrelational databases

In a nonrelational database, you create tables. A table is a place where you can store and query data.

Nonrelational databases are sometimes referred to as “NoSQL databases” because they use structures other than rows and columns to organize data. One type of structural approach for nonrelational databases is key-value pairs. With key-value pairs, data is organized into items (keys), and items have attributes (values). You can think of attributes as being different features of your data.

In a key-value database, you can add or remove attributes from items in the table at any time. Additionally, not every item in the table has to have the same attributes. 

### Amazon DynamoDB

[Amazon DynamoDB](https://aws.amazon.com/dynamodb/) is a key-value database service. It delivers single-digit millisecond performance at any scale.

>  運作方式
> 
> Amazon DynamoDB 是一個全受管、無伺服器、鍵值 NoSQL 資料庫，旨在以任何規模執行高效能應用程式。DynamoDB 提供內建安全性、持續備份、自動多區域複寫、記憶體內快取和資料匯出工具。 
> 
> ![](https://i.imgur.com/TenK3bO.png)

**Serverless**

* DynamoDB is serverless, which means that you do not have to provision, patch, or manage servers. 
* You also do not have to install, maintain, or operate software.

**Automatic scaling**

* As the size of your database shrinks or grows, DynamoDB automatically scales to adjust for changes in capacity while maintaining consistent performance. 

* This makes it a suitable choice for use cases that require high performance while scaling.

**Video transcript**

> AWS Cloud Practitioners, welcome back to the championship chase of the database! In the relational corner, engineered to remove undifferentiated heavy lifting from your database administrators with automatic high availability and recovery provided. You control the data, you control the schema, you control the network. You are running Amazon RDS. Yes, Yeah. 


> The NoSQL corner, using a key value pair that requires no advanced schema, able to operate as a global database at the touch of a button. It has massive throughput. It has petabyte scale potential. It has granular API access. It is Amazon DynamoDB. 


> Head to head. Each database class is engineered to exactly enhance exciting existential environments you envision. Which database will ultimately be victorious in this new world knock out night fight? Once again, the winner will depend on your use case. 


> Round one, Relational databases have been around since the moment businesses started using computers. Being able to build complex analysis of data spread across multiple tables, is the strength of any relational system. In this round, you have a sales supply chain management system that you have to analyze for weak spots. Using RDS is the clear winner here because it's built for business analytics, because you need complex relational joins. Round one easily goes to RDS. 


> Round two, the use case, pretty much anything else. Now that sounds weird, but despite what your standalone legacy database vendor would have you believe, most of what people use expensive relational databases for, has nothing to do with complex relationships. In fact, a lot of what people put into these databases ends up just being look-up tables. 


> For this round, imagine you have an employee contact list: names, phone numbers, emails, employee IDs. Well, this is all single table territory. I could use a relational database for this, but the things that make relational databases great, all of that complex functionality, creates overhead and lag and expense if you're not actually using it. This is where non-relational databases, Dynamo DB, delivers the knockout punch. By eliminating all the overhead, DynamoDB allows you to build powerful, incredibly fast databases where you don't need complex joint functionality. DynamoDB comes out the undisputed champion. 


> Once again, the winner depends on your individual workload. Each service is the right service for specific needs. And once you understand what you need, you will know again, which service is your champion.

### Knowledge check

1. What are the scenarios in which you should use Amazon Relational Database Service (Amazon RDS)? (Select TWO.)

[ ] Running a serverless database

[ ] Using SQL to organize data

[ ] Storing data in a key-value database

[ ] Scaling up to 10 trillion requests per day

[ ] Storing data in an Amazon Aurora database

## Amazon Redshift

**Video transcript**

> We just spent a lot of time discussing the kinds of workflow that require fast, reliable, current data. Databases that can handle 1,000s of transactions per second, storage that is highly available and massively durable. But sometimes, we have a business need that goes outside what is happening right now to what did happen. This data analysis is the realm of a whole different class of databases. Sure, you could use the one size fits all model of a single database for everything, but modern databases that are engineered for high speed, real time ingestion, and queries may not be the best fit. 


> Let me explain. In order to handle the velocity of real time read/write functionality, most relational databases tend to function fabulously at certain capacities. How much content it actually stores. The problem with historical analytics, data that answers questions like, "Show me how production has improved since we started", is the data collection never stops. In fact, with modern telemetry and the explosion of IoT, the volume of data will overwhelm even the beefiest traditional relational database. 


> It gets worse. Not just the volume, but the variety of data can be a problem. You want to run business intelligence or BI projects against data coming from different data stores like your inventory, your financial, and your retail sales systems? A single query against multiple databases sounds nice, but traditional databases don't handle them easily. 


> Once data becomes too complex to handle with traditional relational databases, you've entered the world of data warehouses. Data warehouses are engineered specifically for this kind of big data, where you are looking at historical analytics as opposed to operational analysis. 


> Now, let's be clear. Historical may be as soon as: show me last hour's sales numbers across all the stores. The key thing is, the data is now set. We're not selling any more from the last hour because that is now in the past. Compare that question to, "How many bags of coffee do we still have in our inventory right now?" Which could be changing as we speak. As long as your business question is looking backwards at all, then a data warehouse is the right solution for that line of business intelligence. 


> Now there are many data warehouse solutions out on the market. If you already have a favorite one, running it on AWS is just a matter of getting the data transferred. But beyond that, there may still be a lot of undifferentiated heavy lifting that goes into keeping a data warehouse tuned, resilient, and continuously scaling. Wouldn't it be nice if your data warehouse team could focus on the data instead of the unavoidable care and feeding of the engine? 


> Introducing Amazon Redshift. This is data warehousing as a service. It's massively scalable. Redshift nodes in multiple petabyte sizes is very common. In fact, in cooperation with Amazon Redshift Spectrum, you can directly run a single SQL query against exabytes of unstructured data running in data lakes. 


> But it's more than just being able to handle massively larger data sets. Redshift uses a variety of innovations that allow you to achieve up to 10 times higher performance than traditional databases, when it comes to these kinds of business intelligence workloads. 


> I'm not gonna go into details of how the magic works. We have whole classes that you or your data teams can take that explain how it is built, and why it can return such improved results. The key for you is to understand that when you need big data BI solutions, Redshift allows you to get started with a single API call. Less time waiting for results, more time getting answers.

### Amazon Redshift(亞馬遜紅移)

[Amazon Redshift](https://aws.amazon.com/redshift) is a data warehousing service that you can use for big data analytics. It offers the ability to collect data from many sources and helps you to understand relationships and trends across your data.

>  運作方式 
> 
> Amazon Redshift 使用 SQL 跨資料倉儲、操作資料庫和資料湖分析結構化和半結構化資料，從而使用 AWS 設計的硬體和機器學習在任何規模都能提供最佳價格效能。 
> 
> ![](https://i.imgur.com/IsuMMhj.png)


## AWS Database Migration Service

**Video transcript**

> We've been talking about databases and the various database options on AWS. But what happens if you have a database that's on-premises or in the cloud already? Does that mean you have to start from scratch or does AWS have a magical way to help you migrate your existing database? 


> Thankfully, AWS offers a service called Amazon Database Magic. I mean, Amazon Database Migration Service, or DMS, to help customers do just that. DMS helps customers migrate existing databases onto AWS in a secure and easy fashion. You essentially migrate data between a source and a target database. The best part is that the source database remains fully operational during the migration, minimizing downtime to applications that rely on that database. Better yet is that the source and target databases don't have to be of the same type. 


> But let's start with databases that are of the same type. These migrations are known as homogenous and can be from MySQL to Amazon RDS for MySQL, Microsoft SQL Server to Amazon RDS for SQL Server or even Oracle to Amazon RDS for Oracle. The process is fairly straightforward since schema structures, data types, and database code is compatible between source and target. 


> As I mentioned, the source database can be located on-premises, running on Amazon EC2 Instances, or it can be an Amazon RDS database. The target itself can be a database in Amazon EC2 or Amazon RDS. In this case, you create a migration task with connections to the source and target databases. Then start the migration with a click of the button. AWS Database Migration Service takes care of the rest. 


> The second type of migration occurs when source and target databases are of different types. This is called heterogeneous migrations, and it's a two-step process. Since the schema structures, data types, and database code are different between source and target, we first need to convert them using the AWS Schema Conversion Tool. This will convert the source schema and code to match that of the target database. The next step is then to use DMS to migrate data from the source database to the target database. 


> But these are not the only use cases for DMS. Others include development and test database migrations, database consolidation, and even continuous database replication. 

> Development and test migration is when you want to develop this to test against production data, but without affecting production users. In this case, you use DMS to migrate a copy of your production database to your dev or test environments, either once-off or continuously. 


> Database consolidation is when you have several databases and want to consolidate them into one central database. 


> Finally, continuous replication is when you use DMS to perform continuous data replication. This could be for disaster recovery or because of geographic separation. 


> If you'd like to learn more about any of these, please check out our resources section. And there you have it, folks, DMS in a nutshell.
> 
> 

### AWS Database Migration Service (AWS DMS)

[AWS Database Migration Service (AWS DMS)](https://aws.amazon.com/dms/) enables you to migrate relational databases, nonrelational databases, and other types of data stores.

With AWS DMS, you move data between a source database and a target database. The source and target databases can be of the same type or different types. During the migration, your source database remains operational, reducing downtime for any applications that rely on the database. 

For example, suppose that you have a MySQL database that is stored on premises in an Amazon EC2 instance or in Amazon RDS. Consider the MySQL database to be your source database. Using AWS DMS, you could migrate your data to a target database, such as an Amazon Aurora database.

>
>AWS Database Migration Service (AWS DMS) 可協助您快速安全地將資料庫遷移到 AWS。來源資料庫在遷移期間能夠維持所有功能的運作，將倚賴資料庫之應用程式的停機時間降到最低。AWS Database Migration Service 可以在最廣受採用的商業資料庫及開放原始碼資料庫之間來回遷移您的資料。
>
>AWS Database Migration Service 支援同質遷移 (例如 Oracle 到 Oracle)，也支援不同資料庫平台之間的異質遷移 (例如 Oracle 或 Microsoft SQL Server 到 Amazon Aurora)。使用 AWS Database Migration Service，您還可以以低延遲的方式連續地將資料從任何受支援的來源複寫到任何受支援的目標。例如，您可以從多個來源複寫到 Amazon S3，以建置高度可用且可擴展的資料湖解決方案。您還可以透過將資料串流至 Amazon Redshift，將資料庫合併到 PB 級資料倉儲。進一步了解支援的來源和目標資料庫。
>
>將資料庫遷移至 Amazon Aurora、Amazon Redshift、Amazon DynamoDB 或 Amazon DocumentDB (與 MongoDB 相容) 時，您可以免費使用 AWS DMS 六個月。

**Development and test database migrations**

Enabling developers to test applications against production data without affecting production users

**Database consolidation（數據庫整合）**

Combining several databases into a single database

**Continuous replication（連續複製）**

Sending ongoing copies of your data to other target sources instead of doing a one-time migration

## Additional database services

**Video transcript**

> Before we wrap up databases and storage, I wanna loop back to the topic that we started all this with. Choosing the right database, choosing the right storage platform to fit your business needs, rather than forcing your data to fit your database's requirements. No matter what a database vendor might try to tell you, there is no one-size-fits-all database for all purposes. We've covered quite a few database flavors already, but there are even more databases AWS offers for special business requirements, that we don't have time to cover. But its worth just knowing they are there in case you need them. 


> For example, we talked about DynamoDB, and that's great for key-value pair databases. But what if you need more than just small attributes? What if you need a full content management system? Introducing Amazon DocumentDB, Great for content management, catalogs, user profiles. 


> What if you add a social network that you wanted to track for those kind of social webs, who is connected to who, is very clunky to manage in a traditional relational database so Amazon Neptune: a graph database, engineered for social networking and recommendation engines, also great for fraud detection needs. 


> Or perhaps you have a supply chain, that you have to track with assurances that nothing is lost. Or you have banking or financial records that require 100% immutability, or some people will tell you, oh, that's what blockchain is all about. Well, perhaps, I mean now, If you do need a blockchain solution, wouldn't you know it? We offer Amazon Managed Blockchain. But that's probably not what you really need here. It solves part of the equation, but adds a huge decentralization component, that's not what financial regulators wanna see. What you really need is an immutable ledger, so Amazon QLDB, or Quantum Ledger Database. An immutable system of record where any entry can never be removed from the audits. 


> Databases by themselves are great but if there is a way to make them faster, wouldn't that be greater? But you know I wouldn't be saying that, if there weren't some accelerator options that can be used in a number of unique scenarios. Starting with adding caching layers on top of your databases that can help improve read times of common requests from milliseconds to microseconds Amazon ElastiCache can provide those caching layers without your team needing to worry about the heavy lifting of launching, uplift, and maintenance. And it comes in both Memcached and Redis flavors. 


> Or if you are using DynamoDB, try using DAX, the DynamoDB Accelerator, a native caching layer designed to dramatically improve read times for your nonrelational data. 


> The key thing to understand is, AWS wants to make sure that you using the best tool for the job.


### Additional database services

**Amazon DocumentDB**

[Amazon DocumentDB](https://aws.amazon.com/documentdb) is a document database service that supports MongoDB workloads. (MongoDB is a document database program.)

> Amazon DocumentDB 是一項可擴展、高耐用性和全受管資料庫服務，用於操作任務關鍵型 MongoDB 工作負載。

**Amazon Neptune（海王星）**

[Amazon Neptune](https://aws.amazon.com/neptune) is a graph database service. 

You can use Amazon Neptune to build and run applications that work with highly connected datasets, such as recommendation engines, fraud detection, and knowledge graphs.

>  Amazon Neptune 是快速、可靠的全受管圖形資料庫服務，可讓您輕鬆建置及執行應用程式。 

**Amazon Quantum Ledger Database (Amazon QLDB) **

[Amazon Quantum Ledger Database (Amazon QLDB)](https://aws.amazon.com/qldb) is a ledger database service. 

You can use Amazon QLDB to review a complete history of all the changes that have been made to your application data.

>  Amazon Quantum Ledger Database (QLDB) 是一個全受管總帳資料庫，提供透明、不可變且以密碼編譯方式驗證的**交易日誌**。 
> ![](https://i.imgur.com/5IZgVJK.png)
> 

**Amazon Managed Blockchain**


[Amazon Managed Blockchain](https://aws.amazon.com/managed-blockchain) is a service that you can use to create and manage blockchain networks with open-source frameworks. 


Blockchain is a distributed ledger system that lets multiple parties run transactions and share data without a central authority.

> Amazon Managed Blockchain 是一種全受管服務，可以使用常見的開源架構 Hyperledger Fabric 和 Ethereum 輕鬆建立和管理可擴展的私有網路。
> 
> 運用區塊鏈，能夠建立讓多方都可執行交易的應用程式，無須可信的中央權威機構。 當今，透過現有的技術建置可擴展的區塊鏈網路，設定複雜且難以管理。若要建立區塊鏈網路，每個網路成員需要手動佈建硬體、安裝軟體、建立並管理用於存取控制的憑證，以及設定網路元件。執行區塊鏈網路後，您需要持續監控基礎架構，並適應變化，例如交易請求的增加、新成員加入或離開網路。
> 
> Amazon Managed Blockchain 是一種全受管服務，允許您只要按幾下就能加入公用網路或設定和管理可擴展的私有網路。Amazon Managed Blockchain 消除了建立網路或加入公用網路所需的開銷，並能自動擴展以符合執行百萬筆交易之數千個應用程式的需求。您的網路建立妥當並執行之後，Managed Blockchain 可讓它易於管理和維護您的區塊鏈網路。它可以管理您的憑證並讓您輕鬆邀請新成員加入網路。
> 
**Amazon ElastiCache**

[Amazon ElastiCache](https://aws.amazon.com/elasticache) is a service that adds caching layers on top of your databases to help improve the read times of common requests. 

It supports two types of data stores: Redis and Memcached.

>Amazon ElastiCache 是一項全受管記憶體內快取服務，支援靈活、即時的使用案例。您可以使用 ElastiCache 進行快取，從而提高應用程式和資料庫的效能，或者將其用作無需耐久性的使用案例的主要資料存放區，例如工作階段存放區、遊戲排行榜、串流和分析。ElastiCache 與 Redis 和 Memcached 相容。
>
**Amazon DynamoDB Accelerator（Amazon DynamoDB 加速器）**

[Amazon DynamoDB Accelerator (DAX)](https://aws.amazon.com/dynamodb/dax/) is an in-memory cache for DynamoDB. 
It helps improve response times from single-digit milliseconds to microseconds.

> Amazon DynamoDB Accelerator (DAX) 是適用於 Amazon DynamoDB 的全受管、高可用性記憶體內快取，即使每秒數百萬個請求也能將時間從毫秒縮短到微秒，提供高達 10 倍的效能改進。
> 
> DAX 可執行在 DynamoDB 表新增記憶體內加速所需的繁重工作，開發人員無須管理快取失效、資料母體或叢集管理。
> 
> 現在您可以專注於為客戶建立絕佳的應用程式，無須擔心大規模效能。您不需要修改應用程式邏輯，因為 DAX 與現有的 DynamoDB API 呼叫相容。請參閱 DynamoDB 開發人員指南以進一步了解。
> 
> 只要在 AWS 管理主控台按幾下或使用 AWS 開發套件即可啟用 DAX。和使用 DynamoDB 一樣，您只需支付所佈建的容量費用。在定價頁面進一步了解 DAX 定價。

## Module 5 summary

In Module 5, you learned about the following concepts:

* Amazon EC2 instance store and Amazon EBS
* Amazon S3
* Amazon EFS
* Relational databases and Amazon RDS
* Nonrelational databases and DynamoDB
* Amazon Redshift
* AWS DMS
* Additional database services and accelerators
    
**Video transcript**

> Another module completed. Awesome stuff. You learned about all the different types of AWS storage mechanisms. Let's recap them, shall we? 

> The first one we learned about is Elastic Block Store volumes, and you attach those to EC2 instances so you have local storage that is not ephemeral. 

> You learned about how S3 and how you can store objects in AWS with the click of a button or call of an API. 

> We even discussed the various relational database options available on AWS. Or for the workloads that just need a key-value pair, we have the non-relational offering called DynamoDB. 

> Next up was EFS for file storage use cases. 

> We then have Amazon Redshift for all our data warehouse needs. 

> And to aid in migration of existing databases, we have DMS or Database Migration Service. 

> We also touched upon the lesser known storage services, like DocumentDB, Neptune, QLDB, and Amazon Managed Blockchain. 

> Lastly, we talked about how caching solutions like ElastiCache and DynamoDB Accelerator can be used. 

> That's a lot of places to store different types of data, and hopefully you've learned the correct place to store each type.
> 

### Additional resources

To learn more about the concepts that were explored in Module 5, review these resources.

[Cloud Storage on AWS](https://aws.amazon.com/products/storage)
[AWS Storage Blog](https://aws.amazon.com/blogs/storage/)
[Hands-On Tutorials: Storage](https://aws.amazon.com/getting-started/hands-on/?awsf.getting-started-category=category%23storage&awsf.getting-started-content-type=content-type%23hands-on)
[AWS Customer Stories: Storage](https://aws.amazon.com/solutions/case-studies/?customer-references-cards.sort-by=item.additionalFields.publishedDate&customer-references-cards.sort-order=desc&awsf.customer-references-location=*all&awsf.customer-references-segment=*all&awsf.customer-references-product=product%23vpc%7Cproduct%23api-gateway%7Cproduct%23cloudfront%7Cproduct%23route53%7Cproduct%23directconnect%7Cproduct%23elb&awsf.customer-references-category=category%23storage)
[AWS Database Migration Service](https://aws.amazon.com/dms/)
[Databases on AWS](https://aws.amazon.com/products/databases)
[Category Deep Dive: Databases](https://aws.amazon.com/getting-started/deep-dive-databases/)
[AWS Database Blog](https://aws.amazon.com/blogs/database/)
[AWS Customer Stories: Databases](https://aws.amazon.com/solutions/case-studies/?customer-references-cards.sort-by=item.additionalFields.publishedDate&customer-references-cards.sort-order=desc&awsf.customer-references-location=*all&awsf.customer-references-segment=*all&awsf.customer-references-product=product%23vpc%7Cproduct%23api-gateway%7Cproduct%23cloudfront%7Cproduct%23route53%7Cproduct%23directconnect%7Cproduct%23elb&awsf.customer-references-category=category%23databases)

## Module 5 quiz

1. Which Amazon S3 storage classes are optimized for archival data? (Select TWO.)

[ ] S3 Standard

[ ] S3 Glacier

[ ] S3 Intelligent-Tiering

[ ] S3 Standard-IA

[ ] S3 Glacier Deep Archive

2. Which statement or statements are TRUE about Amazon EBS volumes and Amazon EFS file systems?

[ ] EBS volumes store data within a single Availability Zone. Amazon EFS file systems store data across multiple Availability Zones.

[ ] EBS volumes store data across multiple Availability Zones. Amazon EFS file systems store data within a single Availability Zone.

[ ] EBS volumes and Amazon EFS file systems both store data within a single Availability Zone.

[ ] EBS volumes and Amazon EFS file systems both store data across multiple Availability Zones.

3. You want to store data in an object storage service. Which AWS service is best for this type of storage?

[ ] Amazon Managed Blockchain

[ ] Amazon Elastic File System (Amazon EFS)

[ ] Amazon Elastic Block Store (Amazon EBS)

[ ] Amazon Simple Storage Service (Amazon S3)

4. Which statement best describes Amazon DynamoDB?

[ ] A service that enables you to run relational databases in the AWS Cloud

[ ] A serverless key-value database service

[ ] A service that you can use to migrate relational databases, nonrelational databases, and other types of data stores

[ ] An enterprise-class relational database

5. Which service is used to query and analyze data across a data warehouse?

[ ] Amazon Redshift

[ ] Amazon Neptune

[ ] Amazon DocumentDB

[ ] Amazon ElastiCache

# Module 6: Security

# Module 7: Monitoring and Analytics

# Module 8: Pricing and Support

# Module 9: Migration and Innovation

# Module 10: The Cloud Journey

# Module 11: AWS Certified Cloud Practitioner Basics

# Final Assessment




