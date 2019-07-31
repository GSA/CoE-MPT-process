[CoE Acquisitions](https://github.com/GSA/coe-acquisitions) > CoE MPP process

# CoE MPP
## Welcome Guide

The information in this Welcome Guide should give anyone enough information to understand how the CoE MPP works, how someone can participate in the process, and how to replicate it and adapt it for their own purposes. However, we also included the [Presentations](https://github.com/GSA/CoE-MPP-process/tree/master/Presentations) we've put together as an additional resource. Please give any and all feedback you have through our "[indefinite RFI](https://forms.gle/Lo38qwjTyE7hCPUG7)", which we will never close. Thank you!

## Introduction

With the CoE MPP, various project teams throughout the Government can build a community of private sector partners that can assist them on a per sprint basis, completing work associated with individual and unique user stories. This includes help developing and testing application programming interfaces (APIs), building out existing applications, creating documentation, and developing standards and policies.

Additionally, the minimum requirement that participating contractors [register with SAM.gov](https://beta.sam.gov/signup), the government benefits from expanding the [SAM.gov](https://beta.sam.gov) network while also encouraging non-traditional government contractors to take the first step to join the contractor ecosystem, whether through [IT Schedule 70](https://www.gsa.gov/technology/technology-purchasing-programs/it-schedule-70) using [FASt Lane](https://www.gsa.gov/technology/technology-purchasing-programs/it-schedule-70/sell-through-it-schedule-70/making-it-easier-fast-lane) or [Springboard](https://www.gsa.gov/technology/technology-purchasing-programs/it-schedule-70/sell-through-it-schedule-70/making-it-easier-it-schedule-70-startup-springboard), or any other [Governmentwide Acquisition Contract](https://www.gsa.gov/technology/technology-purchasing-programs/governmentwide-acquisition-contracts-gwacs).

The CoE MPP is not unique in the fact that documenting and sharing best practices in an open and transparent fashion is a key part of what brought it to be and part of what makes the process repeatable and scalable. Examples of previous effforts that we built upon include the following:

1. [Class Deviation 2018-01](https://www.gsa.gov/cdnstatic/Policy_Initiatives/Class%20Deviation%202018-01%20MPT%20and%20SAT%20Increase.pdf), which increased the micro-purchase threshold to $10,000.
2. [FAR Part 13](https://acquisition.gov/content/part-13-simplified-acquisition-procedures), which provides the framework for a FAR-based micro-purchase.
3. [VA Micropurchase Repo on GitHub](https://github.com/department-of-veterans-affairs/VA-Micropurchase-Repo).
4. [cloud.gov’s micro-purchases on GitHub](https://github.com/18F/cg-product/tree/master/micro-purchases).
5. [18F Micro-purchase Marketplace](https://micropurchase.18f.gov/), which is currently archived.
6. [18F Micro-purchase insights](https://micropurchase.18f.gov/insights.html), which provides data related to the marketplace’s operations.
7. [18F Blog posts tagged with "micro-purchase platforms"](https://18f.gsa.gov/tags/micro-purchase-platforms/).

As always, we look to improve what we do as often as we can. Any feedback through the form above would be greatly appreciated!

## How it works
### Before you begin
#### Team dynamics
The CoE MPP isn’t for every project or every team. In order for the CoE MPP to be successful for you, your team must operate in either one- or two-week sprints, have well defined user stories, and strictly adhere to the idea that no individual request should span more than one sprint. Additionally, there will have to be two "Teams of 3" that will be responsible for executing the CoE MPP buy.

#### The two "Teams of 3"
Each member of the both teams should be familiar with the [Agile manifesto](https://agilemanifesto.org/), the [Digital Services Playbook](https://playbook.cio.gov/), and [user stories](https://www.mountaingoatsoftware.com/agile/user-stories).

##### Project Team
A Project Team that wants to use the CoE MPP will require the involvement of a technical subject matter expert that will serve as the Project Team's product owner (Technical SME), the project team’s Director for necessary approvals (Supervisor), and someone who can either provide a signature for or represents the Office of the Chief Financial Officer (OCFO Lead).

#### Acquisition Team
An Acquisition Team that will support a CoE MPP will require the involvement of a dedicated product manager that will serve as the Acquisition Team's product owner (PM), a contracting expert (Acquisition SME), and someone who is or is authorized to act on behalf of a purchase-card holder (P-Card Holder).

#### Tools to use
The use of a collaboration tool, such as (listed in no particular order) [GitHub Project boards](https://help.github.com/en/articles/about-project-boards), [Trello](https://www.atlassian.com/software/trello), [JIRA](https://www.atlassian.com/software/jira), or [Smartsheet](https://www.smartsheet.com/), will allow for the user stories to be discretely defined and backlogs to be appropriately groomed.

### 1. Identifying a user story
#### Finalize the user story
Prior to submission to the CoE MPP, the Project Team should agree among themselves that their user story (or stories, if possible!) is independent enough such that it can be completed by a contractor without the need to access anything other than publicly available information and that the failure of a contractor to complete it will not result in a delay to or failure of a project itself.

#### Create a draft procurement package
The Technical SME will use CoE MPP-specific templates to create first drafts of the following documents:

1. [A market research report](https://github.com/GSA/CoE-MPP-process/blob/master/Documentation/1-Procurement-Package/Market-Research-Report.md).
2. [An independent government cost estimate](https://github.com/GSA/CoE-MPP-process/blob/master/Documentation/1-Procurement-Package/IGCE.xlsx) (IGCE).
3. [A streamlined acquisition plan](https://github.com/GSA/CoE-MPP-process/blob/master/Documentation/1-Procurement-Package/Streamlined-Acquisition-Plan.md).

Any variables that need to be replaced are inside of brackets like {{this-is}}. Prompts are provided using [blockquotes](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#blockquotes), which provide guidance on what should be filled in that section.

#### Confirm funding
Using [this email template](https://github.com/GSA/CoE-MPP-process/blob/master/Documentation/1-Procurement-Package/Approval-Email-Template.md) created for use with the CoE MPP, the Technical SME will obtain emailed approvals, confirming that the Supervisor has approved paying for the project and the OCFO Lead has verified the finances are available for the project.

The amount approved by the Supervisor and the OCFO Lead *must* be the same amount in the IGCE.

#### Submit the user story package
The Technical SME should submit the user story to the Acquisition Team, whether through a Google Form or otherwise.

Once the Technical SME receives a response that the submission has been received, the first of three procurement administrative lead time (PALT) metrics will begin. The PALT will be measured in three parts: first, from the moment a user story was submitted to the moment when the request for responses to the user story goes live on GitHub; second, from the moment the user story goes live on GitHub to the moment a contractor is chosen; and, third, from the moment a contractor is chosen to the moment the user story is considered completed with payment approved.

These three PALTs will allow the Acquisition Team to measure and improve upon their performance while also allowing Project Teams to set their own expectations related to how long the process itself will take.

#### CoE MPP reviews the need
The PM and Acquisition Sme will be responsible for reviewing submissions, creating a new card in whatever project management tool the team has settled on, and moving the process forward. The card must be accessible to all 6 members of the two teams. The Acquisition Team may require information related to the project’s development practices and backlog-related processes for the official contract file. This documentation will help mitigate risks associated with administrative as well as technical issues that may arise.

Once the Acquisition Team has created the card and confirmed need is discrete, appropriately scoped, and contains all the information necessary for an Issue to be posted to the CoE MPP template repository, the Technical SME will be contacted to finalize logistics and timing surrounding the competition.

#### Starting the process
Once the acquisition team has been able to verify everything required has been provided, a purchase folder following the format outlined in the [Documentation](https://github.com/GSA/coe-mpp-process/documentation/) folder will be created by the PM.

The purchase folder must, at a minimum, will have the following documents in each of the following subfolders upon completion of the process:

* 1 Procurement Package
   * A copy of the Project Team's user story submission (eg, Google Form response, email, etc.).
   * A PDF of the approval email thread.
   * A draft market research report using the template provided.
   * A draft IGCE using the template provided.
   * A draft streamlined acquisition plan using the template provided.
* 2 Issue Package
   * A document to collect the questions and answers (Q&A) submitted through the Issue.
   * Templates for the following:
      * New Issue email - An email to send to the contractor community who have subscribed to the CoE MPP mailing list, informing them the Issue has been posted.
      * New Issue tweet - A tweet to promote the Issue to the general public.
      * End of Q&A comment - A comment to post in the Issue once the Q&A period has ended (if applicable).
      * End of advertising period - A comment to post in the Issue once the response period has ended.
* 3 Award Documentation
   * The award decision memorandum.
   * Templates for the following:
      * Award issued comment - A comment to post in the Issue once an award has been issued.
      * Awardee email - An email to send to the Awardee, informing them of the award and confirming the period of performance.
      * Deliverables accepted comment - A comment to post on the merge request of the fork with the deliverables.
* 4 Deliverables
   * The only files in this folder should be those provided by the contractor.
* 5 Closeout Documentation
   * A copy of the verification that the payment was processed.

As needed, the PM or Acquistiion SME will tag the Supervisor and Technical SME throughout the documents as they are being developed. Once all portions of each document are completed and there are no more suggested changes or comments, the package will be considered finalized and sent to the Supervisor and Technical SME for a final approval. After the Supervisor and Technical SME agree everything reflects their need, the PM and Acquisition SME will begin the process of advertising the need.

### 2. Advertising the need
#### Setting the timeline
The PM and Acquisition SME will work with the Supervisor and Technical SME to set the timeline for the posting of the Issue, the end of the Q&A period (if applicable), and the end of the response period. This information will be placed in the Milestones section of the Streamlined Acquisition Plan. Once the target dates for each milestone is finalized, the Issue will be ready to be posted.

#### Posting the Issue
Once the teams have agreed everything is finalized, an Issue will be created in the CoE MPP public repo. This [template repository](https://github.com/GSA/CoE-MPP-template) shows what a CoE MPP public repo would look like in practice.

The PM will also notify contractors through [an update](https://github.com/GSA/CoE-MPP-template#opportunities) to the CoE MPP public repo `README.md` file. For other communications, [templates are provided](https://github.com/GSA/CoE-MPP-process/blob/master/Documentation/2-Issue-Package/Issue-Advertisement-Templates.md) for an email to the listserv created for the purposes of notifying contractors who wish to participate (or whatever else is used to collect interested parties' contact information), and, if applicable, the CoE MPP Twitter account or other appropriate Twitter account.

#### Responding to questions
The PM will gather any questions asked by the contractor community and post them in the [Issue Questions document](https://github.com/GSA/CoE-MPP-process/blob/master/Documentation/2-Issue-Package/Issue-Questions.md). Once the Technical SME and Supervisor provide and sign off on an answer, the PM will respond via the comments in the Issue.

### 3. Issuing an award
#### Reviewing the responses
The PM will work with the Supervisor and the Technical SME to select the best of the submitted responses. Once the review is completed, an [Award Decision Memo](https://github.com/GSA/CoE-MPP-process/blob/master/Documentation/3-Award-Package/Award-Decision-Memo.md) will be completed by the Acquisition SME, submitted to the Project Team for approval, and once approved, finalized by the PM.

#### Announcing the award
The PM will use the [Award Announcment Templates](https://github.com/GSA/CoE-MPP-process/blob/master/Documentation/3-Award-Package/Award-Announcement-Templates.md) to post a comment announcing the award, close the Issue, remove the reference to the Issue on the CoE MPP public repo’s main `README.md` file, and email the awardee.

#### Finalizing the repos
The PM will create [a new folder](https://github.com/gsa/coe-mpp-template/tree/master/yyyy-mm-dd%20User-Story) for the user story in the public repo, add a README.md file, and create another subfolder for [the deliverables](https://github.com/gsa/coe-mpp-template/tree/master/yyyy-mm-dd%20User-Story/Deliverables).

### 4. Approving deliverables
#### No kickoff needed
The Issue itself should contain as much information necessary for a contractor to complete the task without the need for any additional information or a kickoff meeting. The period of performance begins once the awardee is notified that they won, unless otherwise agreed upon by the contractor and government teams or outlined in the Issue itself.

#### Accepting the deliverables
The Supervisor and SME will notify the PM once the deliverables have been completed in accordance with the Definition of Done or acceptance criteria associated with the user story. Upon receipt of this notification, the PM will post a comment from the [Award Announcment Templates](https://github.com/GSA/CoE-MPP-process/blob/master/Documentation/3-Award-Package/Award-Announcement-Templates.md) in the contractor’s merge request, indicating acceptance of the deliverables.

#### Process the payment
The PM will request payment be made to the contractor.

### 5. Closing out the buy
#### Verifying payment
The PM will obtain confirmation of payment (eg, an email from the contractor confirming receipt, a “paid” invoice, etc.). The confirmation should be printed and filed in the `Closeout documentation` folder.

#### Archiving the purchase folder
The PM will rename or move the user story’s purchase folder to make it clear it has been delivered.

## Data to be collected and shared
### Platform-wide metrics
This data will be reported to the public in the [INSIGHTS.md](https://github.com/GSA/CoE-MPP-template/blob/master/INSIGHTS.md) file.

* Average bid
* Average winning bid
* Highest bid
* Lowest bid
* Total bids
* Total unique contractors
* Total unique contractors that are small businesses
* Average number of bids per user story
* Average number of days Issues are open
* Total number of questions received
* Average number of questions per user story
* Average internal PALT (from submission of the user story to award)
* Average official PALT (from posting the Issue to award)
* Average post-award PALT (from award to approval of payment)
* Total subscribers to mailing list

### User-story metrics
This data will be reported to the public in the [award information](https://github.com/GSA/CoE-MPP-template/tree/master/yyyy-mm-dd_User-Story#award-information) section of an awarded user story’s `README.md` file.

## Credits
### Acknowledgements
* [Bridget Fields](https://www.linkedin.com/in/bridget-fields/) for creating this idea.
* [Jon Prisby](https://www.linkedin.com/in/jon-prisby/) for inspiring this idea.
* [Juan Quinones](https://www.linkedin.com/in/juan-quinones-3ab809103/) and Mark Junta for answering questions about the Department of Veterans Affairs similar efforts.
* [Ashley Owens](https://www.linkedin.com/in/ashley-owens-6996b175/), [Mark Hopson](https://www.linkedin.com/in/markchristopherhopson/), [Michelle McNellis](https://www.linkedin.com/in/michelle-mcnellis-9488908/), and [Omid Ghaffari-Tabrizi](https://www.linkedin.com/in/oghaffari/) (in order by first name) for answering questions about how this could be done and providing feedback on the first prototype.
* [David Jones](https://www.linkedin.com/in/devoops/) for providing the first set of feedback from the perspective of a product owner.
* [Bret Mogilefsky](https://www.linkedin.com/in/bretmogilefsky/) for providing lessons learned from cloud.gov’s attempts at doing something similar and feedback from the perspective of a product owner.
* [Brent Maravilla](https://www.linkedin.com/in/brentmar/) for providing lessons learned from USDS's similar efforts for partner agencies.
