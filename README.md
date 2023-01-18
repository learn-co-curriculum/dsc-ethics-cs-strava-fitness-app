# Case Study - Strava Fitness App

## Introduction
In the publication "Data Pollution" (Ben-Shahar, 2019), Omir Ben-Shahar asserts the following:

> *"Digital information is the fuel of the new economy. It is the resource that creates new products and companies, new markets and currencies, and endless new opportunities to create great social value.1 But like the old economy's carbon fuel, it also pollutes. Harmful “data emissions” are spilled into the digital ecosystem, disrupting social institutions and public interests."*

Ben-Shahar continues to develop a novel framework known as *data pollution* to conceptualize the actual and potential harms of the data economy, as well as the regulatory response to these harms. Data pollution is a useful metaphor because it adequately represents the notion that progress can have unintended harms and that any useful tool might also be a useful weapon.

In this case study, you will learn about the **Strava Fitness App** and the impact of the seemingly innocuous app on national security in an international data ecosystem.


## Learning Objectives
You will be able to...

* Describe the main concepts of the **data pollution** framework
* Describe Strava Fitness App in the context of data pollution
* Summarize global efforts of data localization

## Data Pollution
According to Ben-Shahar, the primary public policy challenge of the Information Age is to understand and reduce the magnitude of harm that data pollution presents. Like environmental pollution, data pollution occurs when the data ecosystem is sullied by **data emissions** or events when harmful information is leaked into the data ecosystem, causing disruption to public and social institutions. Ben-Shahar's conceptualization of data pollution also highlights the under-recognized phenom of public harm as a result of information leaks. 

In "Data Pollution", Ben-Shahar writes:

> *"The potential injury to privacy interests—a type of private harm—has been widely remarked upon. The external harms, on the other hand, are less concrete and far less noticed."*

For example, consumers can easily intuit the impact of the **Equifax Data Breach** on individual consumers whose sensitive and personal information was exposed. However, what is less obvious is the impact on public services like the FTC and the IRS who that will have to mitigate the disruption caused by increasingly more common incidents of identity theft. This impacts the budgets of these agencies and absorbs resources needed for other services.

To summarize, **data pollution** is the presence of **data emissions** (harmful information in the data ecosystem), that has been leaked due to some kind of **data breach**. This harmful information might impact consumers on a personal level, but are notable due to actual and potential public harms that they present.

## Strava Fitness App

Strava, known as "the social network for athletes" allows users to post their workout location as they log workouts. Strava then aggregates the the locations of all the users working out at a given time and presents the data points on a global heat map, which was updated in 2018 (4). This allows users to see "hot-spots" where many fellow Strava users are logging a workout. 

### Question 
Can you think of any reasons why this could present a problem to national security? 

Type your response below:


```python
# change me to a markdown cell to type your response.
```

### Answer
**Strava users in the US military continued to share their location with Strava even during their deployment. The clusters of users represented on the map in remote locations in regions of active conflict, inadvertently revealed secret military bases in the desert.**

While seemingly innocuous, Ben-Shahar explains how the app unintentionally compromised national security:

> *"Because the map exposes large concentrated clusters of users in areas of dense activity, it allows
detection of secret geographic locations of U.S. military operations around the
world.13 What else could a cluster of physical workouts in the Sahara Desert, or
in an outskirt of an Afghan city, stand for? It is through the aggregation of the
personal data that a meta-picture emerges, and it threatens a public good—
national security—not the individual privacy of any specific data sharer.*"

## Public Harms
The vulnerability that Strava exposes became international news when, Nathan Ruser, an Australian university student who works with the Institute for United Conflict Analysts posted a view of Strava's heat map. An excerpt from Ruser's post reads:

> *"It looks very pretty, but not amazing for Op-Sec. US Bases are clearly identifiable and mappable."* 

Ruser's observation ignited a discussion about how seemingly safe public data can be misused in dire ways. While the locations of remote bases are sometimes public knowledge, the heat map easily provides insight into areas and times where there is a higher concentration of activity, making those bases more attractive targets for hostile forces. Since the app is most popular with western users,  exercise actives stand out in places like Syria, Yemen, Niger, Afghanistan and Djibouti. 

According to Ruser:

> *"I thought the best way to deal with it is to make the vulnerabilities known so they can be fixed. Someone would have noticed it at some point. I just happened to be the person who made the connection."* (2)

## Policy Response
While it was always possible to turn off location services on the Strava app (a feature that Strava encouraged military users to implement after the incident), many chose not to use it. However, critics of Strava argue that the onus to disable location services should not be on the user and that privacy should be built into the default. 

In response to the incident, the US Department of Defense released a memo providing guidance to deployed service members. (6) Pentagon spokesman Army Col. Robert Manning III stated that:

> *"Effective immediately, Defense Department personnel are prohibited from using geo-location features and functionality on government and non-government-issued devices, applications and services while in locations designated as operational areas.”*

As a result of the change in policy, the Strava heat map of the Pentagon went black. While Strava, offered to assist the Pentagon in their efforts, the government chose to impose stipulations on the members of the military rather than impose regulations on Strava. 


### Data Sovereignty and Data Localization
As governments began to realize the potential for databases to be used in ways that can harm the public good on both and individual and on a national security level. **Data governance** (the processes, roles, policies, standards, and metrics that ensure the effective, efficient, and ethical use of data) has become a hot topi. **Data localization** is a data governance storage strategy that is employed to limit the storage of citizens' data to approved locations. 

One of the drivers influencing governments to adopt a data localization strategy are to protect both public and individual security interests with **digital sovereignty**. Loosely defined, digital sovereignty seeks to create a protective barrier between multinational governments and corporations that might use digital means to exert influence over the citizens of a nation. 

In "Data Pollution" Ben Shahar provides an example:
> *"The Chinese government, for one, declared that “data has become a national basic
strategic resource” and mandated that personal information databases about
Chinese citizens be stored within China. It regards the huge amount of user
information stored by the likes of Alibaba “a serious threat to national security”
if leaked or exposed in unwanted manners (Yanqing 2017)." (1)

The recent CSIS brief __"The Real National Security Concerns over Data Localization"__ (Ramos, et. al., 2021) discusses the United States' role - or lack thereof - in global debates about data governance, including data localization. The authors assert that while the consideration of where data is to be stored and who should access it is of paramount concern to the government, we should be wary of "thinly veiled attempts at asserting greater control of the domestic digital domain" that are justified by the interest of national security. 

> *"[T]here has been little to no debate in the United States about the real national security challenges of data localization and what a viable, alternative model of data governance could look like. This is where a cohesive digital strategy that forms the foundation for a principles-based and consistent approach with like-minded friends and allies will be important."* (2)

In addition, governments recognize that the ultra-targeted personalization of advertisements for goods and services creates profiles that can reveal an alarming amount of personal information about a subject. While the practice of collecting data for targeted advertisements can provide enhanced serviced, the aggregation of such data can also present substantial vulnerability when that data is used to train decision making algorithms without proper context. This has led to the recent implementation of laws such as the **European Union's Global Data Protection Regulation (GDPR).** Other nations, like the United States, benefit from GDPR as many firms that wish to serve European consumers will adopt policies the align with EU regulations.

As of July 2022, about 75% percent of all countries have implemented some level of data localization rules. This impacts how many companies and organizations develop their data infrastructure, to maintain observance of regulations in desirable areas. This has led to increased focus on all areas of data governance. It is seen as a good business strategy to build operations that can flexibly comply with various global policies in our ever-changing data ecosystem. 

## Summary
The Strava Fitness app incident highlights how governments can be blinded to the potential harms presented by new technologies. Harmless information related to workouts can spell big trouble when it is collected from sensitive locations, and governments have begun to react by implementing data governance policies on different levels. While the ideal of digital sovereignty provides an attractive option for governments to protect the data of individuals, citizens should be wary of protectionist policies that might squelch freedom under the guise of national security. 
