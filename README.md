Konstantin Nazarov
==

Currently a DevOps team lead @ Parallels

---

## Contact Information

* e-mail: <mail@racktear.com>
* phone: +7 967 095 89 31
* LinkedIn: [racktear](http://www.linkedin.com/in/racktear)
* Twitter: [@racktear](https://twitter.com/racktear)

## Expertise

* C++/C
* Python
* Understanding of OS internals
* Writing multithreaded and asynchronous code
* Monitoring (nagios and derivatives)
* Jenkins
* Process automation, CI and Continuous Delivery
* Software provisioning with Chef and fabric

## Work Experience

### DevOps Team Lead at Parallels (1.5 years)

Leading a shared DevOps team responsible for continuous delivery, release cycle and development process automation. The team is servicing 3 separate products:

* [Parallels Desktop](http://www.parallels.com/products/desktop/)

  A virtualisation product that allows to run Windows and other OSs on Mac.
  
* [Parallels Cloud Server](http://www.parallels.com/ru/products/pcs/)

  A hypervisor platform for service providers. Can run VMs and containers.

* [Parallels Access](http://www.parallels.com/ru/products/access/)

  Adapts Windows and Mac software for mobile devices.
  
#### Core Responsibilities
* Making sure the products have regular valid builds (at least one a day)
* Adapting products to satisfy the requirements of new OS releases (code signing, application layout, installers etc.)
* Implementing continuous delivery of new product components
* Maintaining build environments, tools and compilers
* Writing tools for developers (with Python as a primary language)
* Maintaining internal storage and computing clouds based on Parallels Cloud Server, including monitoring and disaster recovery

#### Achievements
* Decreased full build time of Parallels Desktop from 4 hours to 1 hour
* Made the whole Continuous Delivery infrastructure more durable by introducing internal computing/storage cloud
* Leading the implemenation of [Parallels Desktop plugin to Vagrant](https://github.com/Parallels/vagrant-parallels)
* Replaced manual provisioning of environments with Chef and fabric
* Moved process automaion from a legacy in-house system written mostly in python to Jenkins. This has signficantly lowered the barrier to entry and allowed to involve developers into CI processes.
* Designed and implemented Continuous Delivery process for [Parallels Access](http://www.parallels.com/ru/products/access/)


### Web Backend Developer at mail.ru (3 months)
Supporting low-level backend components of company's web services (Primarily the email service and news portal). The backend is a set of low-level async network services written in pure C, with Lua as a scripting language.

Left the company after the probation period, because received a more appealing offer from Parallels.

#### Core Responsibilities
* Implementing new components for the backend

#### Achievements
* Implemented asynchronous LDAP authentication library in C, including the partial implementation of LDAP protocol.
* Implemented authentication forwarding in a high-performance mysql proxy


### Algo Trading C++ Developer at Deutsche Bank (2 years)
A member of development team of Autohedger project. Autohedger is a universal algorithmic asset trading platform consisting of a DSL compiler, execution engine and a large set of market connectivity libraries.
The platform is written in C++ with heavy use of boost and multithreading.


#### Core Responsibilities
* Servicing feature requests for new market connectivities
* Improving existing connectivities
* Writing complex state machines for mirroring order lifecycle on the exchange
* Providing SL3 support during outages

#### Achievements
* Implemented an improved version of FIX market connectivity
* Covered the FIX code with extensive set of unit tests and functional tests


### RTOS Kernel Developer at Auriga (2 years)
A member of [LynxOS-178](http://www.lynuxworks.com/rtos/rtos-178.php) development team. LynxOS-178 is a hard real-time POSIX-compatible OS with support for time- and space-partitioned containers.


#### Core Responsibilities
* Kernel-space bug fixing
* Writing tests for checking space and time guarantees of kernel components
* Code review of open-source libraries for inclusion into the OS userspace
* Code certification

#### Achievements
* Significantly improved the state of in-kernel debugging
* Implemented an alternative of 'lsof' utility for LynxOS

### C++ Developer/Sysadmin at OSAN (1 year)
OSAN is a small real estate information aggregator. Its primary business was to trade information between real estate agencies.

#### Core Responsibilities
* Supporting company's IT infrastructure: Active Directory, email, roaming profiles, etc
* Design and development of a time and task tracking software for realtors

### Freelancer (4 years)

At the beginning of my career I tried to sell my skills as an independent developer. Primary customers were small Moscow-based companies with a need for simple accounting software or minor automation, like periodical sending of emails.
