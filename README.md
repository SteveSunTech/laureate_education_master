

### components
| 名称 | master | alibaba |
|:---|:---|:---|
| core | spring cloud netflix Hoxton.SR3  |  spring cloud alibaba 2.2.2.RELEASE  |
| register | spring cloud netflix eureka      |  spring cloud alibaba nacos          |
| configure | spring cloud config              |  spring cloud alibaba nacos          |
| circuit breaker   | spring cloud netflix hystrix    |  spring cloud alibaba sentinel        |
| gateway | spring cloud netflix zuul       |  spring cloud gateway                 |


---

### project
Based on the many years of experience in online education platform development and operation, we are committed to creating a distributed online education system applicable to all industries. The system adopts the front-end and back-end separation mode, the front-end uses vue.js as the core framework, and the back-end uses Spring Cloud as the core framework. The main functions of the system currently include course on-demand function, support for multiple video cloud access, course attachment management function, support for multiple storage cloud access, lecturer management function, support lecturer entry function, which can help individuals or enterprises quickly build a light A massive online education platform.


### front-end
* Home page function, navigation module (customized navigation settings), advertising module (customized carousel settings), course module (customized course settings)
* List function, classification module (custom classification settings), search module (custom search settings)
* Course details page function, course introduction, catalog display and purchase, playback function, etc.
* Personal center, with functions such as personal information setting, password modification, order management, learning records, etc.
* Lecturer center, lecturer information management, course management (addition and modific

### back-end
* Authority management function, multi-role multi-user custom configuration
* System configuration function, custom site configuration and third-party parameter configuration
* Lecturer management function, lecturer applies for settlement, the backstage has audit function
* Course management function, the lecturer manages his own courses, and the backstage has an audit function
* Order management function, order list, order analysis and statistics function
* User login function, only allow the same account to log in at the same place at the same time to prevent account sharing
* Advertising management function, background custom advertising settings, increase marketing effects
* Payment function module, seamless docking [Dragon Fruit Payment System Commercial Edition](https://pay.roncoo.net/)

