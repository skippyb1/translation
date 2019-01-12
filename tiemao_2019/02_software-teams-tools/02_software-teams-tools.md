# Tools For Software Engineering Teams

# Web开发团队必备的软件

The effect of poorly performing web applications echoes across various parts of the business. The more breakage there is, the more busy support teams get. There is less traction, and product teams are puzzled about user retention. Engineers are inundated with bug-fixes, leaving no time for feature development. Business stakeholders receive no insight into performance improvements. Engineering managers cannot clearly justify the efforts being taken. The list goes on. 


如果Web应用的性能不行, 就会影响到相关的各种业务。
如果系统漏洞很多, 运营团队就会疲于奔命. 
如果缺少各种监控数据, 产品经理可能会对用户行为困惑。

开发永远改不完的BUG, 自然没时间去进行性能优化. 
业务方更受不了响应迟钝的系统。
但项目经理却没有证据来表明整个团队做了哪些努力。

类似这样的情形经常会出现。

What are the available options to keep this risk at bay? The answer lies in providing your development team with the right kind of tools they can use to deal with common problems that arise from each stage in software development.

怎样控制和防范这些风险呢? 这就需要开发团队, 在不同的项目阶段, 引入合适的工具。

## Planning tools

## 任务计划排期

The beginning of most software products/projects lies in planning and tracking development. Planning tools are used from the time a project begins until the time a project is under active development. Planning a project is the start of every iteration in cyclical project management followed in most places today. It is justified as helping herd cats, or prevent yak shaving. The most common tool is [Jira](https://www.atlassian.com/software/jira). There are a few alternatives too which engineering teams pick up based on their needs. 


大多数软件产品/项目从一开始就伴随着开发计划的发展变更。计划工具跨越整个项目开发周期, 从项目开始前, 到开发完成. 在大多数时候, 每个项目迭代都需要进行规划。可以是合理的硬核计划, 也可以是为了防止无限期拖延. 最常用的工具是[Jira](https://www.atlassian.com/software/jira)。 当然也有其他的备选方案, 开发团队可以根据需要自己选择。

## Version control tools

## 版本控制工具

Gone are the days when the person holding the rubber duck is the only one who can make changes to the source code. Version control is the first tool that every engineering team decides upon before anything else. Even among small teams or hobby projects with a single programmer, version control is employed. Engineering teams have a clear choice among [Git](https://git-scm.com/), Mercurial, and [Apache Subversion](https://subversion.apache.org/)provided by several vendors. There is immense maturity in the realm of version control, as a result of which teams know exactly what they’re getting into.

只准单人进行代码修改的日子一去不复返, 随着软件工程的规模越来越庞大, 版本控制工具是每个团队都必须先确定好的。优先级高于一切! 即便是小团队或者单人开发, 版本控制都是必须的选择, 有句话说: “无版本、不编程！” 

比较成熟的工具包括 Git, SVN, Mercurial 等等。 当然现在Git是最优先的选择。

> 关于Git, 请参考: <https://blog.csdn.net/renfufei/article/details/41647875>


## Testing tools

## 测试工具

Nearly every engineering team in the world that does web application development uses [Selenium](https://www.seleniumhq.org/) in their testing environment. When deployed using the [Robot Framework](http://robotframework.org/), a generic test automation setup is available for acceptance testing. It provides a powerful way of asserting if applications work, and gives a good sanity check for the laundry list of requirements. 


世界上几乎每一个工程团队,web应用程序开发中使用(硒)(https://www.seleniumhq.org/)在他们的测试环境.当部署使用(机器人框架)(http://robotframework.org/),一个通用的测试自动化设置用于验收测试.它提供了一个强大的断言,如果应用程序的工作方式,并给出了一个好的完整性检查清单的要求。

## CI/CD tools

## CI/CD工具

With a change in the way software was developed, it was only natural for the methods of software release to evolve as well. To facilitate faster release cycles, where teams released software more frequently, the CI/CD pipeline was conceived. This stands for the combined practices of continuous integration and continuous delivery. [Jenkins](https://jenkins.io/), [Travis](https://travis-ci.org/), and [CircleCI](https://circleci.com/) are among the most popular tools used by engineering teams to have functional CI/CD pipelines.

软件开发方式的改变,只有软件发布的方法自然进化.促进更快的发布周期,团队更频繁地发布软件,CI / CD管道设计.这代表了持续集成和持续交付的实践相结合。(Jenkins)(https://jenkins.io/),特拉维斯(https://travis-ci.org/),和[CircleCI](https://circleci.com/)是最常用的工具功能CI / CD管道工程团队。

## Configuration tools

## 配置工具

The fundamental goal of configuration tools is to manage large-scale infrastructure efficiently. Some of the ancillary goals are to minimize interference and input required from engineers and sysadmins, reduce complexity involved in configuring distributed infrastructure. [Ansible](https://www.ansible.com/) is the most prevalent tool, and alternatives like [Chef](https://www.chef.io/chef/), [Puppet](https://puppet.com/), and [Salt](https://www.saltstack.com/) are available too.

配置工具的基本目标是有效地管理大规模的基础设施.一些辅助的目标是最大限度地减少干扰和输入需要从工程师和系统管理员,降低复杂性参与配置分布式基础设施。[Ansible](https://www.ansible.com/)是最普遍的工具,选择像(厨师)(https://www.chef.io/chef/),(傀儡)(https://puppet.com/),和(盐)(https://www.saltstack.com/)是可用的。

## Monitoring tools

## 监控工具

This is a very scattered space at the moment. That said, there is enormous evolution happening with monitoring tools. Early monitoring tools began to inspect server parameters when software was released and used these as indicators of application health. Correlation existed between how the server held up and what a user experienced. This approach unfortunately raises more questions than it actually answers. Today, there is a shift in this paradigm owing to different evolutions in browsers, communication protocols, and other pieces. It is possible to record the experience of a user by attaching agents to the browser. 


这种援助space at the mr。,,乌兹别克斯坦与监测工具happening……………….早期监测工具began to inspect server参数的获释和递解所用软件的应用这些健康指标.相关的服务器之间存在了什么用户体验。这种方法很不幸引发了更多的问题比实际的答案.今天,有一个转变这种模式由于不同的浏览器中演进,通信协议和其他碎片.可以记录用户的经验通过附加代理到浏览器。

There is also a lot of effort invested in areas like log management, alerting, telemetry, and reporting in the name of monitoring. Some of these are valid. Logging security events, meaningful alerting, resource utilization are valuable parameters to track, but only if accompanied by a clear strategy of monitoring users. A handful of tools like [Zabbix](https://www.zabbix.com/), [Nagios](https://www.nagios.org/), and [Prometheus](https://prometheus.io/) are used by engineers, but none of them solve the problem of real-user monitoring.

还有很多努力投入日志管理、报警、遥测和报告的监控。这些都是有效的.记录安全事件,有意义的警报,资源利用率是有价值的参数跟踪,但前提是伴随着监控用户的一个清晰的策略.A handful Zabbix][工具like(https://www.zabbix.com/)案,[Nagios][https://www.nagios.org/),和(https://prometheus Prometheus](.使用io /)工程师,但是没有一个解决这个问题的真实用户监控。

Simply investing in software will not help you mitigate your performance problems. There are many steps you need to take to be able to get there. It is not for the faint-hearted, or for the easily-distracted. Tuning web applications for good performance is a serious commitment and requires enormous effort to do well. It also demands discipline to maintain web applications that way. The returns that await teams who undertake this effort are huge!

只投资于软件不会帮助你减轻你的性能问题。有许多步骤你需要能够到达那里.它需要胆量,或者容易分心。web应用程序调优性能良好是一个严肃的承诺,需要巨大的努力做得很好.它还要求纪律维护web应用程序的方式。回报,等待团队进行这方面的努力是巨大的!

Please remember – performance is about people. About your users.

请记住——性能是人。关于你的用户。

We’re all united in our goal to make software faster, and provide a reliable digital user experience. There are many means to achieve this end, [Plumbr](https://www.plumbr.io/) being one among them. Plumbr provides a real-user monitoring system that provides performance insights based on the interactions of your users. [Sign up today for a free trial](http://app.plumbr.io/signup), and stay on top of performance issues faced by your users.

我们都团结在我们的目标软件更快,并提供一个可靠的数字的用户体验。实现这一目的的手段有很多,(Plumbr)(https://www.plumbr.io/)是其中之一.Plumbr提供了一个真实用户监控系统,提供基于用户的交互性能的见解。注册一个免费试用)今天(http://app.plumbr.io /注册),并保持你的用户所面临的性能问题。

<https://plumbr.io/blog/devops/tools-for-software-engineering-teams>



December 19, 2018

2018年12月19日
