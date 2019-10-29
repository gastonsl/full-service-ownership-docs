![Implementing](../assets/img/FullService_Implementing.png)

Whether it is an individual contributor or an organizational shift, introducing new practices in organizations is hard. It's essential to understand how people and organizations process change, as well as accepting that change does not happen overnight. It is critical to align business values, key outcomes, and expectations, along with open and frequent communication to see success in the adoption of new practices. Where wide-scale organizational change often necessitates a top-down model, full-service ownership can be done through the bottoms-up model.

The bottoms-up model of change involves buy-in and involvement in the decision making process from individuals impacted by a proposed change. Using the collective approach and starting small allows teams, managers, and leaders to prove success to the broader organization. To demonstrate progress, you have to understand where you started and be able to articulate the impact of the changes made.

## Aligning Values with Metrics and Engineers
The best way to prove success is through the use of metrics. The first step is determining which metrics align with company values and then baselining and tracking improvements in those metrics. Some metrics provide very in-depth levels of insight. For those who are just implementing the full-service ownership model; MTTA, MTTR, incident count, and major incident impact are the base level measurements teams should be analyzing.

Once an incident is triggered, the clock starts ticking on both MTTA and MTTR. Optimizing the response process through streamlined on-call mechanisms has a positive impact on both measurements by removing the chaos and bringing in the expert right away.

Measuring the impact of major incidents can be done with a simple graph where X represents time and Y represents the number of customers affected. The sample chart below references a critical incident, as the impact is growing over time. The bigger the area under the trend line, the more severe an incident is. The area under the curve and the time it takes to start going down illustrates the impact on customers.

![incidentimpact chart](../assets/img/incident_impact.png)

_For more information on how PagerDuty classifies incidents, check out the [Incident Response Guide](https://response.pagerduty.com/before/severity_levels/)._

Any transformation involves gaining buy-in from stakeholders. With the bottom-up approach to change, stakeholders are brought into the decision-making process. As full-service ownership transforms the way teams operate, bringing engineers as the stakeholders into the conversation, and gaining commitment to the shared business values is essential. Engineers are service owners, which in turn makes them the subject matter expert (SME) and accountable to the reliability and security of the things they build and the customer experience. With increasing complexity, on-call brings the ability to leverage automation, streamlined processes, tools, and best practices to support the practice of full-service ownership through accountability as the SME.

## Start Agile, Small, and New
Agile is an essential methodology to have in place when implementing full-service ownership.  Using Agile methodologies keeps everyone on the same page by embedding the notion that a team is collectively responsible for their outputs. Starting with sprint planning and using daily scrum standups will assist in identifying things that are going well and potential blockers. The combination of sprint planning, daily scrums, sprint reviews, and sprint retrospectives keeps the individuals and team aligned to the overall goal and objective and provides consistent learning feedback loops. Information sharing is key to a team's success by allowing anyone to "pick up the pager" and act as the SME for an incident or alert.

Massive organizational transformation takes significant time and executive sponsorship. Gaining top-level buy-in necessitates the demonstration of return on investment (ROI). Similar to how organizations use a Proof of Concept (POC) to evaluate the ROI of new software, teams can implement the POC model to document the ROI of the full-service ownership model. Start with one or two small teams who currently embrace Agile best practices as the teams to prove out the ROI. However, there may be some cases where it is necessary to bring new people into the organization who are experts in both Agile and DevOps practices if there is an absence of knowledge in the organization. Beyond starting with one to two small teams, on those teams, start with one service/ application. Just as infants begin with rolling over, crawling, walking then running; the start small approach gives teams the stepping stones to master the mechanics of full-service ownership.

Along with starting agile and small, greenfield projects will be the most successful in the POC phase. Greenfield projects and new architectures give engineers the ability to optimize alerting and notifications based on best practices versus legacy services or monolithic applications which require an in-depth alerting review. Perfection is the enemy of adopting new processes, and adjustments can be hard. Jumping in with both feet on small reliable services or systems is an excellent way to start on-call rotation.

## Embrace a Blameless Culture
Change is scary, especially when changing how a team and individuals operate. Successful adoption of full-service ownership requires more than engineers taking responsibility for their code, but also a culture of honesty, acknowledgment, and trust. Individuals need to be empowered to make decisions efficiently and should not fear blame during an incident.

During incidents, especially major customer-impacting incidents, on-call individuals are frequently required to make informed in the moment decisions. One of the worst situations on-call individuals can face is paralysis by no-decision. A blameless culture can alleviate these fears and allow engineers to get to work efficiently, fixing the problem. A thriving blameless culture has management buy-in and is based on honesty, learning, and accountability. Setting ground rules for how incidents are managed is one way to facilitate empowerment. PagerDuty incident response is a great starting point on what to do before, during, and after an incident, including different roles and call etiquette.

Fostering a blameless culture through psychological safety will alleviate many challenges associated with new ways of working. Individuals need to feel they can speak up regarding concerns or struggles they may be facing. [The 2019 Accelerate State of DevOps Report](https://cloud.google.com/devops/state-of-devops/) by DORA affirmed previous research done by [Google](https://rework.withgoogle.com/blog/five-keys-to-a-successful-google-team/) on the effects of psychological safety on performance:

>“Our analysis found that this culture of psychological safety is predictive of software delivery performance, organizational performance, and productivity. Although Project Aristotle measured different outcomes, these results indicate that teams with a culture of trust and psychological safety, with meaningful work and clarity, see significant benefits outside of Google.”

It is also essential to understand that not everyone will be willing to embrace the change necessary to move forward. A variation of the Pareto Principle known as the 20/60/20 rule illustrates this: 20% of individuals will be early adopters who are excited to learn and try new things, 60% will be on the fence, and the final 20% will be detractors. Focus on the 20% of early adopters first, as they will be the most likely to succeed in the new process and will champion the 60% through the change. For the 20% detractors, there may be a moment where unwillingness to work as a team won't allow for their continued presence within the organization. As undesirable as attrition is, it is merely a facet of change that must be accepted. However, by setting the team up for success through starting small, agile, greenfield, and blameless and showing successful results, attrition rates may be mitigated.

## Team Structure
Team structure is a crucial element of the full-service ownership methodology and should be taken into consideration when implementing an on-call call schedule. Outside of small organizations, full-service ownership is best implemented on a team with a minimum of three members, which allows for one member to be entirely off rotation at some point during the schedule. Devoting time to onboarding team members to full-service ownership/on-call will add another layer of success to the process. For teams with established on-call practices, having new employees shadow the on-call team as part of the onboarding is a great way to reduce stress and set proper expectations. For teams new to the process, starting with a schedule during work hours or with a 24-hour rotation is another way to establish success.

Practicing empathy for full-service owners will also lead to the successful adoption of on-call. With any on-call strategy, individuals may be woken up in the middle of the night, on their weekends and holidays, or during the workday. Showing empathy to each other during this time dramatically reduces the stress associated with on-call. If a team member who is on-call comes in later in the day, take a moment to understand that they may have been paged in the middle of the night and took some time to recuperate.

## Testing, Deployment, Code Reviews, and Automation

In the Agile development model, continuous integration is a key component that falls within the full-service ownership framework. With continuous integration, code is written and tested in small chunks. From there code can be continuously deployed into production, allowing for smaller rollbacks if needed. By properly testing these small chunks of code, developers are ensuring their changes won't adversely affect the existing code, reducing the risk of potential outages. Using automation for testing and deployment cuts down on time to market while still assuring quality and cutting down on alerts due to poor performing code.

[The Test Driven Deployment (TDD)](https://en.wikipedia.org/wiki/Test-driven_development) methodology by Kent Beck is an excellent method of testing in the full service ownership model:

> “TDD is a [software development process](https://en.wikipedia.org/wiki/Software_development_process) that relies on the repetition of a very short development cycle: requirements are turned into very specific [test cases](https://en.wikipedia.org/wiki/Test_case), then the software is improved to pass the new tests, only. This is opposed to software development that allows software to be added that is not proven to meet requirements.”

Code reviews are a sure-fire way to establish a non-siloed environment on a full-service ownership team. By implementing code reviews, two things occur; the team itself all becomes vested in safeguarding the code in production and team members all function as SMEs, thus establishing the ability to be more successful if there is an alert during an on-call rotation.

"Automate everything" should be the mantra a full-service ownership team lives by. From unit testing to CI/CD, if it can be automated, it should be. Automation cuts down on time to market and increases reliability. Automation goes beyond testing and must be incorporated into how alerts and incidents are handled. Runbooks are a significant first step in automating to a full-service ownership on-call team. Runbooks are the first step in incident management, with baked-in procedures used as a reference when something goes awry. Instead of having a physical book, incorporating the runbook automation allows for repeatable processes defined by actions taken during the alert or incident.

## Shadowing and Making Code Changes
Along with daily standups, implement a shadowing program for all new engineers. When a team configures shadowing the goal is to simulate the process and actions of going on call as precisely as the team can, while making sure that actions of the "Shadow User" do not affect the primary engineer who is actually on call. This results in the Shadow User becoming confident and comfortable with our processes, while the primary on-call responder can still carry out their actions undeterred.

Ensure knowledge bases, runbooks, and playbooks are all up-to-date and give team members time to familiarize themselves with these resources to maximize knowledge sharing across the team. Team members in full-service ownership organizations should always feel comfortable reaching out to others during incidents if they are unfamiliar with the proper resolution pathways.

When a team member is making a lot of changes, testing a new feature, or refactoring a lot of code, have that team member own the on-call during this time. This keeps the alert noise down for other members of the team and allows the engineer to address any issues arising from their changes quickly.

## Practice and Collaborate
As with almost anything, practice allows individuals to be more confident with change. With on-call, there can be a fair amount of stress when an incident is triggered. By having team members go through simulated incidents, they will be calmer when a real incident occurs.

Chaos engineering techniques such as Failure Fridays, are an excellent way to practice full-service ownership on-call. Failure Fridays are a weekly practice of injecting failure scenarios into infrastructure. While many organizations choose to practice Failure Fridays in production; these can also be practiced in testing or in hypothetical situations. The main goal is to familiarize individuals with how alerts come in, what steps to take, and what incident response looks and feels like.

 Beyond familiarizing team members with the new process, Failure Fridays will also result in more resilient systems and services, and will ensure alerting is set-up correctly for your systems.

Additionally, Failure Fridays are a great place to test all of the alerts that have been added for any new service to ensure they are working.  A few things to test for are:

* Test that the alert threshold is set appropriately to reduce noise alerting.
* Test that you get alerted for the “No Data” condition if applicable. Generally, receiving no data is the same as breaking your threshold.
* Test that the alert resolves automatically when the metrics return to normal.

From increased learning to a heightened awareness of what team members are working on, collaboration serves many benefits. In the full-service ownership on-call model, collaboration is crucial for success before, during, and after an incident. Collaboration happens in many ways. Specifically to incident management, collaboration best practices ensure members who are part of the full-service ownership team and individuals in other areas of the organization can work together and are informed during an incident. On-call incident management collaboration best practices include:

*   Call bridge and video for real-time collaboration for the response team and stakeholders
*   Chat room where members can join to have real-time communication and are able to work together to fix the issue. This also serves as a great tool for documentation for the post-mortem
*   Assigning roles: to avoid the bystander effect; assigning roles to responders assists everyone in keeping members on the same page and ensuring a quick resolution time during an incident. To see how PagerDuty assigns roles check out the [Incident Response Document](https://response.pagerduty.com/training/overview/)