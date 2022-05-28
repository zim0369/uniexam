# Questions

**These are the questions from SKN's recent(May 2022) prelim examinations**

1.  **Define virtualization and write down different types of virtualization.**
    **Explain Network and Storage Virtualization in detail.**

    *   Virtualization in cloud computing allows a provider to virtualize
        servers, storage, or other physical hardware or data center resources,
        which can then, in turn, allow them to provide numerous services such as
        infrastructure, software, and platforms.

    *   The 7 Types of Virtualization
        1.  OS Virtualization—aka Virtual Machines
        2.  Application-Server Virtualization
        3.  Application Virtualization
        4.  Administrative Virtualization
        5.  Network Virtualization
        6.  Hardware Virtualization
        7.  Storage Virtualization

    *   **Storage Virtualization:**
        *   Storage virtualization in Cloud Computing is nothing but the sharing
            of physical storage into multiple storage devices which further
            appears to be a single storage device. It can be also called as a
            group of an available storage device which simply manages from a
            central console.

        *   This virtualization provides numerous benefits such as easy backup,
            achieving, and recovery of the data.

        *   This whole process requires very less time and works in an efficient
            manner. Storage virtualization in Cloud Computing does not show the
            actual complexity of the Storage Area Network (SAN). This
            virtualization is applicable to all levels of SAN.

    *   **Network Virtualization:**
        *   Network Virtualization is a process of logically grouping physical
            networks and making them operate as single or multiple independent
            networks called Virtual Networks.

        *   Tools for Network Virtualization :
            1.  **Physical switch OS:** It is where the OS must have the
                functionality of network virtualization.
            2.  **Hypervisor:** It is which uses third-party software or
                built-in networking and the functionalities of network
                virtualization.

        *   Advantages of Network Virtualization :
            1.  Improves manageability
            2.  Improves utilization
            3.  Enhances performance
            4.  Enhances security

2.  **Explain virtualization in grid.**

    *   **NEEDS REFACTORING**

    *   Virtualization allows addressing multiple problems in Grid systems, such
        as coping with the heterogeneity of Grid resources, the difference in
        software stacks, and enhanced features in resource management such as
        more general check pointing or migration models. Adopting virtualization
        in smart ways gets us closer to real Grid computing with more ﬂexibility
        in the type of applications and the resources to use.

<!-- TODO: Virtualization in grid -->

3.  **Explain Virtual Clustering in detail.**

    *   **NEEDS REFACTORING**

4.  **Explain CPU virtualization in detail.**

    *   CPU Virtualization is a hardware feature found in all current AMD &
        Intel CPUs that allows a single processor to act as if it was multiple
        individual CPUs.This allows an operating system to more effectively &
        efficiently utilize the CPU power in the computer so that it runs
        faster.

    *   CPU Virtualization improves performance and efficiency to a greater
        extent because virtual machines work on a single CPU, sharing resources
        is actually like using multiple processors at the same time. This saves
        Cost and Money.

    *   Types of CPU Virtualization
        1.  **Hardware-assisted CPU Virtualization :** Hardware supports CPU
            Virtualization through certain processors like Guest User. This Uses
            different versions of code and the mode is known as a Guest mode.

        2.  **Software-based CPU Virtualization :** This type of CPU
            Virtualization is software-based and it helps application code to get
            executed on a processor.

        3.  **Virtualization and Processor-Specific behavior:** Although this
            software virtualizes the CPU, the virtual machine can detect the model
            of a processor on which it is running, processor models may differ in
            CPU features they offer and applications running on these CPUs may use
            these features.

    *   [Need more info?](u2.1.md#cpu-virtualization)

5.  **Explain in detail Amazon Web Services & its components.**

    *   Amazon Web Services, Inc. is a subsidiary of Amazon that provides
        on-demand cloud computing platforms and APIs to individuals, companies,
        and governments, on a metered pay-as-you-go basis. These cloud computing
        web services provide distributed computing processing capacity and
        software tools via AWS server farms.

    *   Amazon Web Services (AWS) is the world’s most comprehensive and broadly
        adopted cloud platform, offering over 200 fully featured services from
        data centers globally. Millions of customers—including the
        fastest-growing startups, largest enterprises, and leading government
        agencies—are using AWS to lower costs, become more agile, and innovate
        faster.

    *   AWS Components:

        1.  **Data Management and Data Transfer:** To run HPC applications in
            the AWS cloud, you need to move the required data into the cloud. There
            are several data transport solutions designed to securely transfer huge
            amounts of data. This overcomes issues like a long time for transfer,
            high network costs, and security concerns. Also, you can automate the
            movement of data between the AWS cloud and on-premises storage. There
            are options for establishing a private connection to the AWS from your
            premises. This increases bandwidth to provide more throughput, reduces
            the cost of the network, and provides a consistent network experience.

        2.  **Compute & Networking:** There are several compute instances types
            that can be customized according to your needs. It also handles
            monitoring your application and adjusting its capacity for maintaining a
            steady and predictable performance at an affordable cost. Also, setting
            up application scaling across multiple services for multiple resources
            takes a few minutes. Enhanced networking options from AWS allow
            achieving lower inter-instance latency and higher bandwidth.

        3.  **Storage:** When looking for an HPC solution, you need to consider
            the storage options and cost. There are several flexible blocks, object,
            and file storage options in AWS services that allow permanent and
            transient data storage. It allows allocating storage volumes according
            to the size you need. You can store and access and data type over the
            cloud without doing a data migration project. Also, with AWS services,
            you can transfer your workload to the cloud from on-premises.

        4.  **Automation and Orchestration:** For using the infrastructure
            efficiently, you need to automate scheduling submitted jobs and the job
            submission process. AWS services allow you to run thousands of batch
            computing jobs through the dynamic provision of the computer resources
            on the basis of the requirements.

        5.  **Operations and Management:** As a system administrator, you are
            responsible for avoiding cost overruns and monitoring the
            infrastructure. There are several management and monitoring services
            that allow you to optimize utilization of resources, monitor the
            application, get a complete view of operational health, and respond to
            the performance changes.

        6.  **Visualization:** With the AWS services, you can easily visualize
            the engineering simulations’ results without moving huge amounts of
            data. Now, you can access the interactive applications remotely over a
            standard network and deliver application sessions to any workstation.

        7.  **Security and Compliance:** For running applications on the cloud,
            you need to have an understanding of regulatory compliance and security
            management. There are several quick-launch templates and security
            related services offered by AWS that helps in protecting data and
            customer privacy by putting strong safeguards in the AWS
            infrastructure.

6.  **Explain in detail Elastic Cloud Computing(EC2).**

    *   **Amazon Elastic Compute Cloud** is a part of Amazon.com's cloud-computing
        platform, Amazon Web Services, that allows users to rent virtual computers
        on which to run their own computer applications.

    *   Features of Amazon EC2:
        *   **Functionality:** EC2 provides its users a true virtual computing
            platform, where they can various operations and even launch another
            EC2 instance from this virtually created environment. This will
            increase the security of these virtual devices. Not only creating
            but also EC2 allows us to customize our environment as per our
            requirements, at any point of time during the life span of this
            virtual machine. Amazon EC2 itself comes with a set of default
            AMI(Amazon Machine Image) options supporting various operating
            systems along with some pre-configured resources like RAM, ROM,
            storage, etc. Besides these AMI options, we can also create an AMI
            curated with the combination of default and user-defined
            configurations. And for future purposes, we can store this
            user-defined AMI, so that next time, the user won’t have to
            re-configure a new AMI from scratch. Rather than this whole process,
            the user can simply use the older reference while creating a new EC2
            machine.
        *   **Operating Systems:** Amazon EC2 includes a wide range of operating
            systems to choose from while selecting your AMI. Not only these
            selected options, but users are also even given the privileges to
            upload their own operating systems and opt for that while selecting
            AMI during launching an EC2 instance. Currently, AWS has the
            following most preferred set of operating systems available on the
            EC2 console.
            *   Amazon Linux
            *   Windows Server
            *   Ubuntu Server
            *   SUSE Linux
            *   Red Hat Linux

7.  **Explain in detail Azure core concepts.**

    *   Microsoft Azure, often referred to as Azure, is a cloud computing service
        operated by Microsoft for application management via Microsoft-managed data
        centers.

    *   Azure core concepts:

<!-- TABLE -->

| Concept Name        | Description                                                                                                                                                                                                                                                           |
|---------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Regions**         | Azure is a global cloud platform which is available across various regions around the world. When you request a service, application, or VM in Azure, you are first asked to specify a region. The selected region represents datacenter where your application runs. |
| **Datacenter**      | In Azure, you can deploy your applications into a variety of data centers around the globe. So, it is advisable to select a region which is closer to most of your customers. It helps you to reduce latency in network requests.                                     |
| **Azure portal**    | The Azure portal is a web-based application which can be used to create, manage and remove Azure resource and services. It is located at https://portal.azure.com.                                                                                                    |
| **Resources**       | Azure resource is an individual computer, networking data or app hosting services which charged individually. Some common resources are virtual machines( VM), storage account, or SQL databases.                                                                     |
| **Resource groups** | An Azure resource group is a container which holds related resource for an Azure solution. It may include every resource or just resource which you wants to manage. |
| **Resource Manager templates**                                                                                                                                                                                                                                        | It is a JSON which defines one or more resource to deploy to a resource group. It also establishes dependencies between deployed resources. |
| **Automation:**                                                                                                                                                                                                                                                       | Azure allows you to automate the process of creating, managing and deleting resource by using PowerShell or the Azure command-line Interface(CLI). |
| **Azure PowerShell**                                                                                                                                                                                                                                                  | PowerShell is a set of modules that offer cmdlets to manage Azure. In most cases, you are allowed to use, the cmdlets command for the same tasks which you are performing in the Azure portal. |
| **Azure command-line interface(CLI)**                                                                                                                                                                                                                                 | The Azure CLI is a tool that you can use to create, manage, and remove Azure resources from the command line. |
| **REST APIs**                                                                                                                                                                                                                                                         | Azure is built on a set of REST APIs help you perform the same operation that you do in Azure portal Ul. It allows your Azure resources and apps to be manipulated via any third party software application. |

8.  **Explain in detail cloud computing applications:**
    *   **Healthcare:** Cloud computing in healthcare describes the practice of
        implementing remote servers accessed via the internet to store, manage
        and process healthcare-related data. This is in contrast to establishing
        an on-site data center with servers, or hosting the data on a personal
        computer.

        *   **ECG Analysis in the cloud:**

            *   **ECG analysis in cloud computing**: cloud computing
                technologies allows the remote monitoring of a patient's heart
                beat data. Through this way the patient at risk can be
                constantly monitored without going to the hospital for ECG
                analysis. At the same time the Doctor's can instantly be
                notified with cases that need's their attention.

            *   An ECG is just a visual image of a record of the electrical
                activity of the heart muscle as it varies over time, typically
                printed on paper for easier study. Similarly, like other
                muscles, the heart contracts in response to electrical
                depolarization caused in the muscle cells. When it's the time of
                day, it's the amount of the electrical activity, when amplified
                and registered for just a few seconds that we call a heart
                rhythm.

            *   With ECG data collection and tracking, it's possible to test for
                chest pain, low-grade heart rhythm disturbances, arrhythmias,
                and more. An E-G (electrocardiogram) is the electrical
                expression of the contractile movement of the myocardium.

    *   **Biology:** Cloud computing is an emerging technology that provides
        various computing services on demand. It provides convenient access to a
        shared pool of higher-level services and other system resources.
        Nowadays, cloud computing has a great significance in the fields of
        geology, biology, and other scientific research areas.

        *   **Protein Structure Prediction:**

            *   Protein structure prediction is the best example in research
                area that makes use of cloud applications for its computation
                and storage.

            *   A protein is composed of long chains of amino acids joined
                together by peptide bonds. The various structures of protein
                help in the designing of new drugs and the various sequences of
                proteins from its three-dimensional structure in predictive form
                is known as a Protein structure prediction.

            *   Firstly primary structures of proteins are formed and then
                prediction of the secondary, tertiary and quaternary structures
                are done from the primary one. In this way predictions of
                protein structures are done. Protein structure prediction also
                makes use of various other technologies like artificial neural
                networks, artificial intelligence, machine learning and
                probabilistic techniques, also holds great importance in fields
                like theoretical chemistry and bioinformatics.

9.  **Explain different types of risks in cloud computing.**

    *   In many ways, the security threats facing today’s traditional data
        center environments overlap with those of a cloud computing environment.
        On both sides, cybercriminals aim to take advantage of vulnerabilities
        found in software.

    *   There are several security risks to consider when making the switch to
        cloud computing. Here are 5 of the top security risks your organization
        should be aware of:

    1.  **Data Loss:** Data loss is the most common cloud security risks of
        cloud computing. It is also known as data leakage. Data loss is the process
        in which data is being deleted, corrupted, and unreadable by a user,
        software, or application. In a cloud computing environment, data loss occurs
        when our sensitive data is somebody else's hands, one or more data elements
        can not be utilized by the data owner, hard disk is not working properly,
        and software is not updated.

    2.  **Hacked Interfaces and Insecure APIs:** As we all know, cloud computing
        is completely depends on Internet, so it is compulsory to protect interfaces
        and APIs that are used by external users. APIs are the easiest way to
        communicate with most of the cloud services. In cloud computing, few
        services are available in the public domain. These services can be accessed
        by third parties, so there may be a chance that these services easily harmed
        and hacked by hackers.

    3.  **Data Breach:** Data Breach is the process in which the confidential
        data is viewed, accessed, or stolen by the third party without any
        authorization, so organization's data is hacked by the hackers.

    4.  **Vendor lock-in:** Vendor lock-in is the of the biggest security risks
        in cloud computing. Organizations may face problems when transferring their
        services from one vendor to another. As different vendors provide different
        platforms, that can cause difficulty moving one cloud to another.

    5.  **Increased complexity strains IT staff:** Migrating, integrating, and
        operating the cloud services is complex for the IT staff. IT staff must
        require the extra capability and skills to manage, integrate, and maintain
        the data to the cloud.

    6.  **Spectre & Meltdown:** Spectre & Meltdown allows programs to view and
        steal data which is currently processed on computer. It can run on personal
        computers, mobile devices, and in the cloud. It can store the password, your
        personal information such as images, emails, and business documents in the
        memory of other running programs.

    7.  **Denial of Service (DoS) attacks:** Denial of service (DoS) attacks
        occur when the system receives too much traffic to buffer the server.
        Mostly, DoS attackers target web servers of large organizations such as
        banking sectors, media companies, and government organizations. To recover
        the lost data, DoS attackers charge a great deal of time and money to handle
        the data.

    8.  **Account hijacking:** Account hijacking is a serious security risk in
        cloud computing. It is the process in which individual user's or
        organization's cloud account (bank account, e-mail account, and social media
        account) is stolen by hackers. The hackers use the stolen account to perform
        unauthorized activities.

10. **Explain in detail cloud security services:** *Confidentiality,*
    *Integrity, &* *Availability*

    *   The three letters in "CIA triad" stand for Confidentiality, Integrity,
        and Availability. The CIA triad is a common model that forms the basis
        for the development of security systems. They are used for finding
        vulnerabilities and methods for creating solutions.

    *   The core principles of information security and data governance—data
        confidentiality, integrity, and availability (known as the CIA
        triad)—also apply to the cloud:
        *   **Confidentiality:** protecting the data from unauthorized access
            and disclosure
        *   **Integrity:** safeguard the data from unauthorized modification so
            it can be trusted
        *   **Availability:** ensuring the data is fully available and
            accessible when it’s needed

    *   [More details about CIA](u2.3.md#data-security-in-cloud)

11. **Explain in detail different types of risks in Cloud Computing.**

    *   Refer question 9

12. **Explain need of secure cloud software requirements.**

    *   You need a secure way to immediately access your data. Cloud security
        ensures your data and applications are readily available to authorized
        users. You'll always have a reliable method to access your cloud
        applications and information, helping you quickly take action on any
        potential security issues.

    1.  **Top-of-the-Line Perimeter Firewall:** Most firewalls are very
        simple—they typically inspect a packet’s source and destination and that’s
        all. Some more advanced firewalls feature stable packet inspection, which
        checks the integrity of the file packets for stability issues prior to
        approving or rejecting the packet.

    2.  **Intrusion Detection Systems with Event Logging:** Numerous IT security
        compliance standards require businesses to have a means of tracking and
        recording intrusion attempts. So, for any business that wants to meet
        compliance standards such as PCI or HIPAA, using IDS event logging solutions
        is a must.

    3.  **Internal Firewalls for Individual Applications, and Databases:** While
        having a strong perimeter firewall can block external attacks, internal
        attacks are still a major threat. Infrastructures that lack internal
        firewalls to restrict access to sensitive data and applications cannot be
        considered secure.

    4.  **Data-at-Rest Encryption:** Encrypting the data that is stored on your
        cloud infrastructure can be an effective way to keep your most sensitive
        information from being accessed by the wrong party.

    5.  **Tier IV Data Centers with Strong Physical Security:** The physical
        hardware used to run a cloud environment represents one last opportunity for
        hackers and industrial spies to steal your most important data. When allowed
        direct access to the hardware that runs the cloud, hackers have free reign
        to steal data or upload malware directly to your systems.

13. **Explain future trends in cloud computing.**

    *   Future Trends in Cloud Computing

        1.  **Hybrid/ Multi-Cloud Solutions:** Hybrid cloud computing refers to
            using a combination of the private cloud as well as a third-party public
            cloud service. It is primarily used to allow workloads to move between
            private and public clouds, giving users more flexibility with their
            computing needs.

        2.  **Backup And Disaster Recovery:** Cyber attacks, data outages, and
            system failures are a part and parcel of running a business these days.
            Most businesses have dealt with their servers crashing, leading to loss
            of critical data files. To ensure such issues don’t damage the
            organization and its processes, backup and disaster recovery has become
            a trending use case of the cloud. If Spiceworks reports are to be
            believed, 15% of the cloud budget is allocated to Backup and Disaster
            Recovery, which is the highest budget allocation followed by email
            hosting and productivity tools.

        3.  **Serverless Architecture:** A serverless architecture removes all
            barriers that a standard IT infrastructure would usually bring. Users
            don’t have to purchase or rent the servers that they run their data on.
            Instead, a third-party will handle it all for you, allowing your
            organization to tackle other tasks.

        4.  **AI Platform:** As technology advances, one of the most common
            cloud computing trends to look forward to is AI. Tech giants are now
            looking into incorporating AI to process big data to improve their
            business functioning.

        5.  **Cloud Security:** Data theft, leakage, and deletion- security is a
            big challenge even for traditional IT infrastructures. But, with more
            companies moving to cloud platforms, it’s important to ensure that cloud
            service providers can create an airtight security system to guarantee
            the safety of their client’s data.

        6.  **IoT Platform:** With a hyper-connected world, one of the most
            popular cloud computing trends is the rise of IoT platforms. A study by
            Gartner suggests the number of connected things in use will be going up
            to 25 billion by 2021 from 14.2 billion as of 2019.

        7.  **Edge Computing:** It is a method of optimizing cloud computing
            network system by performing data processing at the edge of the network,
            near the source of the data. It works real-time on the cloud servers to
            process less time-sensitive data or store data for the long term.

        8.  **DevSecOps:** Cloud computing services provide users with a
            seamless and simple experience in managing their data but there are many
            security risks involved.  The security risk of cloud computing includes
            network eavesdropping, illegal invasion, denial of service attacks, side
            channel attacks, virtualization vulnerabilities, and abuse of cloud
            services.

        9.  **Service Mesh:** Since cloud platforms are complex, it is critical
            to ensure that the platform has a fast and safe communication
            environment. With a service mesh, users have a dedicated layer for
            service-to-service communication, making their cloud platform highly
            dynamic and secure.

        10. **Open Source:** This industry is moving towards a path of
            innovation and collaboration. With this shift in how cloud services are
            managed, many organizations are looking at adopting an Open Source
            cloud computing service for their business.

14. **Explain Docker and Kubernetes in detail.**

    *   Docker is a set of platform as a service products that use OS-level
        virtualization to deliver software in packages called containers. The
        service has both free and premium tiers. The software that hosts the
        containers is called Docker Engine.

    *   [More Details](https://www.geeksforgeeks.org/introduction-to-docker/)

    *   Kubernetes is an open-source container orchestration system for
        automating software deployment, scaling, and management. Google
        originally designed Kubernetes, but the Cloud Native Computing
        Foundation now maintains the project.

    *   [More Details](https://kubernetes.io/docs/concepts/overview/)

15. **Explain Mobile Cloud in detail:** *Key requirements,* *Automatic cloud
    computing, &* *Comet cloud*

    *   Key requirements:

        *   Cloud infrastructure: Cloud infrastructure is a specific form of
            information architecture that is used to store data.

        *   Data cache: In this, the data can be locally cached.

        *   User Accommodation: Scope of accommodating different user
            requirements in cloud app development is available in mobile Cloud
            Computing.

        *   Easy Access: It is easily accessed from desktop or mobile devices
            alike.

        *   Cloud Apps facilitate to provide access to a whole new range of
            services.

    *   [Refer for Mobile Cloud](u2.4.md#mobile-cloud)

    *   [Refer for Automatic Cloud Computing](u2.4.md#automatic-cloud-computing)

    *   [Refer for Comet Cloud](u2.4.md#comet-cloud)

16. **Explain the IoT and cloud in automobile.**

    *   [Refer for IoT and cloud in your automobile](u2.4.md#the-iot-and-cloud-in-your-automobile)
