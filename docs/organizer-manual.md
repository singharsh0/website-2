This manual will document the common tasks that an Outreachy organizer has during the Outreachy application phase and internship.

# Organizer private resources

 * Public GitHub [Outreachy website repository](https://github.com/outreachy/website/)
 * Public GitHub [repository for Outreachy creative works and miscellaneous scripts](https://github.com/outreachy/creative-works-and-scripts/)
 * Public etherpad for taking notes during Outreachy organizer meetings (ask an organizer for the URL before the meeting)
 * Private GitLab [notes repository](https://gitlab.com/sagesharp/outreachy-notes/) for organizers
 * Private GitLab [eligibility notes repository](https://gitlab.com/sagesharp/outreachy-applicant-review)
 * Private Software Freedom Conservancy [subversion repository](svn+ssh://svn@basswood.sfconservancy.org/Conservancy/Projects/Outreachy) for storing intern and mentor agreements, sponsorship agreements, and the Outreachy finances ledger files. Only Outreachy PLC members have access to this via ssh key.
 * Invite-only [Zulip chat](https://chat.outreachy.org/) for Outreachy interns, mentors, coordinators, and organizers
 * [Invoice Ninja account](https://www.invoiceninja.com/) for tracking invoices
 * [Organizer dashboard](https://www.outreachy.org/dasboard/) for sending semi-automated emails and tracking progress during the internship round
 * [Rackspace account](https://mycloud.rackspace.com/) for managing Outreachy web servers
 * [Announce mailing list](https://lists.outreachy.org/cgi-bin/mailman/admin/announce) admin interface
 * [Community mailing list](https://lists.outreachy.org/cgi-bin/mailman/admin/community) admin interface (depreciated in favor of the Zulip chat, but occasionally gets spam that needs to be deleted)
 * [Mentor's mailing list](https://lists.outreachy.org/cgi-bin/mailman/admin/mentors) admin interface
 * [Opportunities mailing list](https://lists.outreachy.org/cgi-bin/mailman/admin/opportunities) admin interface

# Pre-application period

**Date: August 6 / Jan 6**

Two weeks before the initial application period opens, organizers start trying
to find communities and mentors to participate.

## Subscribing Tapia Sign-ups

Each year, Outreachy has a booth at the Tapia conference. We talk to potential
applicants. They can sign up to be added to the announcements mailing list. We
collect email addresses through an Open Data Kit survey, with tablets running an
Android app called kobotools.

The end result is a exported .ods (Libre Office spreadsheet) with contact
information. That year's contact information is commited in the GitLab notes
repository in a folder named tapia-YEAR (e.g. tapia-2019).


If this is the May to August round, subscribe to the announcements mailing list
any students who signed up at the Tapia booth who were only interested in the
May round. We don't subscribe them to the announcements mailing list until after
all the emails from the December round have been sent.

The mailing list interface will ask for a message to send them when subscribing
them to the mailing list. Use the message in the GitLab notes repo file named
email/email-tapia-welcome-to-mailing-list.txt

For the December to March round, Tapia falls during the initial application
period. Sign up all people who expressed interest in the December round
immediately. Also sign up anyone who said they weren't interested in applying,
but wanted to be subscribed. This is generally people who have already graduated
or are teachers, who want to help spread the word about Outreachy.

## Announcing Mentor CFP

Send an email to the mentor's mailing list (template email in the Private GitLab
notes repository in the file email/email-open-round-mentor-cfp-to-mentors-list.txt)

After subscribing any Tapia sign-ups for the May round, send an email to the
announce list for a call for mentors (template email in the Private GitLab notes
repository in the file email/email-open-round-mentor-cfp-to-announce-list.txt)

There will sometimes be communities who have privately contacted Outreachy
organizers expressing interest in participating. Send them a separate email with
the CFP info, since they may not be on the announcement mailing list.

We typically document community interest in the round folder in a file called
communities.txt. For example, communities that expressed interest in the May
2020 round would be in 2020-05-round/communities.txt. We also sometimes document
that in the etherpad. Find the community status for the last round and see which
communities said they wanted to participate in this round.

## Pinging continuing sponsors

**Date: August 13 / Feb 28**

During the last week of the internship, ping continuing sponsors. Remind them
about the opportunities list, and ask if they can continue their sponsorship
for the next round.

Email template is in the private organizers repository, in the file
`email/email-sponsor-end-of-round-opportunities-list-and-continuing-sponsorship.txt`

You can see notes on who is a general funding sponsor, when they donate, and
which communities they earmark funds for, in the private Invoice Ninja account.

Look in the Invoice Ninja client tab for notes on the sponsors. Look in
invoices and search for 'general' to find general fund sponsors. Search for
'any' to find sponsors who earmark funding for any community. Other sponsors
are typically contacted by communities.

## Pinging coordinators

**Date: August 13 / Jan 13**

The opening of the round usually falls after the winter holidays or in August
when many mentors in the Northern Hemisphere are on vacation. Coordinators
sometimes miss them, so it's important to individually ping them a week after
the CFP has been announced.

Before pinging the coordinators, make sure you're aware if their community has
any internship sponsorship credits from previous rounds. A community may have
credits if a sponsor earmarked funds for them, or an intern was terminated. You
can find out what credits communities have by looking at Invoice Ninja.

It's also good to be aware of whether the organization participated in the last
round, or why they couldn't participate. That's usually documented in the
etherpad. E.g. see the "Outreachy communities for Dec 2019 round" section. You
can look up past conversations with community coordinators by searching for "in
Outreachy" in the subject line of the organizer's email box in the
common/organizer/old folder.

## Mentor and coordinator subscriptions

**Date: Aug 13 - Dec 10 / Jan 13 - May 30**

Mentors and coordinators have two ways of keeping connected to the Outreachy
community. They have the private mentor's mailing list, and they can also keep
in contact with other interns in the Outreachy Zulip chat.

As coordinators for new communities are approved, or new mentors are approved,
you will need to manually subscribe them to the mentor's mailing list and the
Outreachy Zulip chat:

 - Go to the [trusted contacts
   list](https://www.outreachy.org/dashboard/trusted-volunteers/), which shows
   all participants from approved communities (approved mentors and approved
   coordinators). This list is only accessible to people who have "staff"
   privileges on the Outreachy website.

 - Go to the [mentor's mailing list subscription
   page](https://lists.outreachy.org/cgi-bin/mailman/admin/mentors/members/add).
   You'll need to have the admin password for the mentor's mailing list. Sage has
   that password. Subscribe people to the list with an invitation message like the one in
   the private GitLab repo, in email/email-mentor-welcome-mailing-list.txt. Make
   sure to update the dates for the current round.

 - When you subscribe mentors to the list, mailman will let you know which ones
   were successfully subscribed. Everyone else already was subscribed, and thus
   probably already has access to the Zulip chat. Only invite those new
   subscribers to the Outreachy Zulip chat.

 - In the Outreachy Zulip chat, go to the settings gear in the upper right, then
   click 'Invite users'. Add the new subscribers to the list to invite. Give the
   mentors and coordinators access to the following streams:

    - introductions
    - mentors & coordinators (private stream)
    - chat
    - conferences
    - connections - location & language
    - help
    - internship procedures questions
    - thank you!
    - victories

This needs to be done several times each round. I usually do it every Monday.
This also needs to be done about a week into the internship, as some mentors get
added as co-mentors when the internship starts.

# Reviewing projects

Occasionally a coordinator asks us about how to determine if a project should be approved.

Here's the questions I asked a coordinator:

1. If this is a new feature, is it likely to be accepted by the
community? We don't want to have interns work on something that won't be
merged upstream.

2. Is the community ready to maintain any new features the intern
contributes? Interns aren't required to stick around after the
internship is done, and the community needs to be ready to maintain that
project. For instance, if your intern creates a new repository, make
sure it's under the community organization on GitHub and that community
members have push access to it.

3. Is the mentor who is proposing this new project a long-standing
contributor to the community? Someone who is a knowledgable contributor
will be able to identify any risks in a new project. Integrated
community members can help shepherd the discussion around a new feature.

4. Is this new feature or project critical path? We try to have mentors
avoid giving interns projects that are time-critical.

5. Will the intern get a good amount of interaction with the community?
We try to have intern projects that allow interns to understand what
it's like to communicate and collaborate with a community. If they're
working on something new completely on their own, they may not get that
experience.

# Updating contracts

**Date: August 20 / Jan 20**

Update the mentor agreement (docs/mentor-agreement.md) and intern agreement
(docs/intern-agreement.md) to have the correct round dates. Change the 'last
updated' date.

You can see what needs to change each round by looking at the git commits to
that file.

# Initial application period opens

**Date: August 20 / Jan 20**

Send personalized emails inviting anyone who signed up at the Tapia booth to
apply for that round. Email templates are in the GitLab notes repository in files
named email/email-tapia-dec-mar-potential-applicants.txt and
email/email-tapia-may-potential-applicants.txt.

You can use a Python script to automatically generate personalized emails. The
script is in the GitHub creative works and misc repo. The script file is
code/emailgeneric.py. You'll have to pass in command-line arguments for the
email template, csv file with contacts, and directory to generate emails in.
The script will generate text files you can pass into the email client mutt to
send. You can send emails with the following mutt command:

`for i in `ls .`; do mutt -F ~/.muttrc-outreachy -H $i; rm $i; done`

Send emails to our standard list of organizations. You can find the list of
organizations in the GitLab private repository in the file
contacts/promotion.txt.

Pay and submit job advertisements for the websites listed in
contacts/promotion.txt.

# Intern selection period

After final applications are closed, the following steps need to be taken:

 - Mentors select one or more interns for their project
 - Coordinators set the funding source for each intern
 - Outreachy PLC members approve or reject any general funding requests
 - Outreachy organizers approve or reject any additional interns

## Conflicting intern selections

In the case where applicants are selected for multiple projects, we go
through a few steps:

0. Are there enough co-mentors for the project such that the interns will have
a 1:1 mentor ratio? If one community has more interns than they have mentors,
then the applicant should be an intern for the other community.

1. Start a discussion with the mentors about the quality of the
applicant's contributions.

Mentors - Has NAME shown they have the skills to be a successful intern?
Are their contributions of high quality? Have they been consistent about
communicating with mentors? Have they been consistently contributing?

2. Does one project have another strong applicant they want to accept?

If one project has no other strong applicants, the preference is that
applicant interns with that project. The goal is to have as many interns
as possible.

3. What is the source of the intern funding for both projects?

There is a slight preference from the Outreachy organizers to have
the intern accepted by a community who is funding them from community
sponsors. This maximized the number of interns we can accept.

4. What is the intern's preference?

If both mentors still want to accept the applicant after the
discussion, the Outreachy organizer should contact the applicant and
ask them which project they want to work on.

## Coordinating with Google Summer of Code

If the internship aligns with Google Summer of Code, some Outreachy applicants may have applied for both Outreachy and Google Summer of Code.

If the applicant applied for the same project under both programs, or even the same community but a different project, Outreachy organizers generally let Outreachy community coordinators handle talking with the GSoC org admin.

If the applicant has applied for a community that isn't participating in Outreachy, we try to coordinate with that community. Ideally, they would let us contact the applicant and ask which program they want to work under. That's not always possible, as some GSoC orgs want to stick with the Google Summer of Code rule to not talk about their intern selections until the announcement date.

The Outreachy final application has a question about which GSoC orgs the person is applying to, and what the mentor's contact info is. There's an email template in the Organizer's private GitLab notes repo for contacting the community.

## Intern Selection Checking

When reviewing all interns, please do the following:

 * **Resolve any intern conflicts** The Outreachy website will email all project mentors and coordinators when an intern is selected by more than one project. Go to the organizer's email and facilitate any conversation around that conflict. Sometimes an intern has made substantially more contributions to one project. In that case, ask whether the other mentor is okay with the applicant being accepted under the other project. If the mentors can't make a decision, then you can email the applicant to ask them to choose.
 * **Review applicant strength** Applicants with a ranking of 2 ("Inexperienced - smaller contributions that vary in quality") or below should not be accepted. If the intern was marked as a 3 ("Good - some smaller contributions of good quality"), review their contributions and amount of time available for the internship. If their contributions are minor one-liners and they have less than 2/3rds of the internship period free (typically less than 60 / 90 days free), then we may not want to accept them. Following up with the mentors about the strength of the applicant can be informative, since sometimes applicants have made contributions that they didn't record them in the website.
 * **Review applicant time commitments** Click the applicant's name on the dashboard to be taken to their detailed application and time commitment information. If an applicant said they would quit their job, email them to a) double check if their stated weekly hours is correct and b) double check whether they will quit that job, if required. It's required that applicants quit their jobs if they work more than 20 hours a week, or if they're working in a technical role and they're being accepted for a technical position. There's an email template in the Outreachy organizer's private GitLab eligibility repository that you can use.
 * **Check final applications for mentions of jobs or other time commitments** Sometimes applicants aren't truthful, and don't include all their time commitments on their initial application. If you notice they mention a job or classes, email them with a sternly worded warning and ask questions about their time commitments.
 * **Check for mentors over-committing themselves** Review all the mentors in each community. If one mentor has selected two interns, ask if they have a co-mentor who can help them. If they don't, and the community is new to Outreachy, tell them they shouldn't select more than one intern.

### Intern strength checking

If you see an applicant who doesn't seem strong (e.g. ranked as a 3),
send the following email to the mentor and coordinator:

I've been checking on the strength of selected Outreachy interns. I have
some concerned about your intern selection.

I noticed that you selected APPLICANT for the COMMUNITY project
"PROJECT". You rated them as a RATING.

I looked through their contributions, and I noticed CONCERN.

1. How has the applicant shown they have the skills to be a successful
   Outreachy intern?
2. How has the applicant shown they have good communication skills?
3. How often does the applicant ask questions when they're stuck?
4. How often have they been in contact with mentors?
5. Have they joined the community's public chat? How active are they?

In order for the internship to be successful, we need Outreachy mentors
to only accept applicants who have a good chance of being successful. We
especially look for applicants who have strong communication skills and
are in contact with their mentors.

Outreachy organizers view this internship as a fellowship. Mentors
should not expect a certain project to be completed by the intern, but
rather expect that the intern's work will be adjusted to the level of
their ability, their interests, and the project's priorities throughout
the internship.

If you are unsure of the applicant's skills for this project, are you
flexible with modifying the project tasks to fit the applicant's skills?

## Invoicing

### Billing Information

During the intern selection period is a good time to ask for billing information for sponsors. The email template for that is in the organizer private GitLab notes repo.

We use Invoice Ninja to track invoices, their status, and internship credits for future round. We do *not* send invoices using the Invoice Ninja interface. Only save invoices as a draft.

### Community Credits

Community or sponsor credits happen in a number of ways:

 * Sometimes a community is billed early for a specific number of interns. If a community wants to accept less interns then they were billed for, there will be a credit.
 * Some sponsors that are grandfathered in only want to donate to a particular community. If that community accepts less interns than they have sponsorship for, there will be a credit.
 * Some sponsors that are grandfathered in only want to donate to intern funding for any communities. If we have less interns that were accepted for the Outreachy general fund, there will be a credit.
 * An intern fails, and we don't send them their internship stipend. The remaining stipends that were not send (e.g. mid-point or final stipend) is recorded as a community credit.

Credits are recorded as an "Expense" in Invoice Ninja. The "Project" is the community (or any interns) that the credit should go towards. The private notes sections documents how much the sponsor was originally invoiced for, the invoice number, the remaining credit, and which communities in which round we've already used this funding for.

Before invoicing a community for this round, always check in Invoice Ninja expenses to see if they have a credit.

## Adding Draft Invoices

Make sure to add the sponsor contact details and invoice draft to Invoice Ninja. There is a particular format for setting the invoice number that makes it easier to search: `RoundDate-InvoiceNumber-CommunitiesThatReceiveThisFunding`. If an invoice spans multipe rounds, add the second round after the invoice number. That way when you search for all sponsors that donated to a particular round, the past invoice will show up.

Keep track of the status of the invoice in the private notes field. Note when it was sent to Conservancy. Change the invoice sent date to be the Friday after intern selection announcement. If the sponsor wants to be invoiced later than that, set the sent date to be in the future.

## Sponsorship Logos

When Outreachy announces the accepted interns, we should have all sponsor logos displayed on the [Outreachy website homepage](https://www.outreachy.org) with the right prominance for their sponsorship amount. Sponsorship levels are on the [sponsorship page](https://www.outreachy.org/sponsor).

You can edit the logos on the homepage by going to the [Wagtail admin interface](https://www.outreachy.org/admin/) choosing 'Pages' from the sidebar, and clicking the pencil icon for the first page that shows up. Add a logo by clicking the plus button between logos in the right sponsorship level section. Use the image uploader to upload an image, and tag it with 'sponsor logo' and 'sponsor'. You can search for logos we've used in the past that are already uploaded.

Sponsor logos are stored in the GitLab private notes repository, under `graphics/sponsor-logos`.

## Sponsor Twitter Handles

When we announce the accepted Outreachy interns, we want to thank our sponsors on Twitter. This requires collecting sponsor Twitter handles. Some are recorded in Invoice Ninja in the 'Clients' priviate notes. Most are missing because there's an obvious Twitter handle to use. Some open source communities have no handle, in which case we just include their text name.

Some sponsors have a yearly donation. We credit their sponsorship level each round as half the amount of their yearly sponsorship. Some sponsors are rounded up to the next sponsorship level if the amount is very close (e.g. within a thousand dollars or so). Check the past history of the home page to see how those yearly sponsors have been credited, or just leave their logos in the same place.

We create an individual tweet, thanking each ceiling smasher and equalizer sponsors. All Promotor sponsors are thanked in one tweet. Includer sponsors all get thanked in one or two tweets.

General format:

 * `Congratulations to the NUMBER interns accepted for the @outreachy ROUND internships! https://www.outreachy.org/alums/`
 * The @outreachy internships wouldn't be possible without the support of our sponsors.
 * Thank you to the Outreachy Ceiling Smasher sponsor @HANDLE! We appreciate their [commitment to/continued support towards] @outreachy, and improving diversity in free and open source software.
 * We'd like to thank our Equalizer sponsor @HANDLE! It's awesome to see COMPANY supporting diversity in free and open source software.
 * A big thank you goes to our Equalizer sponsor @HANDLE! We appreciate their continued support of @outreachy and diversity in free and open source software.
 * Outreachy is so thankful for our Promoter sponsors @HANDLE, @HANDLE, @HANDLE, and @HANDLE. Thank you for supporting diversity in free and open source software!
 * Outreachy would also like to thank our Includer sponsors @HANDLE, @HANDLE, @HANDLE, @HANDLE, @HANDLE, and @HANDLE.

## Invoice and Logo Prep

Once all Outreachy interns have been accepted or rejected by the Outreachy organizers, it's time for prepping invoices, getting sponsor logo prominence correct, and creating the draft Twitter announcement tweets.

The process is:

 * Go to the [Outreachy dashboard](https://www.outreachy.org/dashboard) and confirm that every intern selection that is marked as being funded by community sponsors has a corresponding invoice in Invoice Ninja. Ensure the amount of sponsorship is correct. Some communities have more funding earmarked for them than they will accept interns. Most communities don't want to be invoiced for future interns, but some do. Check with the community coordinator. If the community already has been invoiced, or wants to be invoiced for more interns then they accepted, record the community credits in the 'Expenses' section. Record which community the credit is for in the project field of the expense.
 * *Record past used credits* Look at all interns who are marked for general funding sponsorship. Look through the past credits for 'Any intern'. Apply those past credits by recording in the notes which community intern and round they went to. If a credit is completely used, mark it as paid and archive it.
 * *Apply sponsor funding for any intern* Look at sponsors for this round who wanted to sponsor any interns. Note in the private notes which communities and round that went to.
 * *Record new community credits* If a sponsor's funding for any intern for this round was not used, record it as a credit in the 'Expenses' section under the 'Any intern' project. Sponsors who donate to the Outreachy general fund without a stipulation that it go towards intern funding don't need to be recorded as a credit.
 * *Delete unused invoices* If a community had sponsorship and they haven't been billed, but they won't accept any interns this round, delete the invoice. This involves comparing the community names in the invoice numbers to the list of all interns marked for community sponsor funding.
 * *Fix sponsor logo prominence on Outreachy website* Now that the invoice list is finalized, filter the list by this round date (e.g. 2019-05). That will filter on the invoice number. Sort by sponsor name and then sort again by sponsor amount. Go through the website and ensure all sponsors are credited at the right prominence.
 * *Remove old sponsor logos* Compare the list of sponsors on the Outreachy website. Remove any sponsors that aren't being invoiced this round. Double check the Conservancy svn repository in the `Agreements/Sponsorship` folder for any yearly sponsorship agreements. Ensure you don't delete a yearly sponsor that is receiving credit for half their sponsorship this round.

## Invoicing Sponsors

When invoicing sponsors, always check the invoice sending date and notes field. Some sponsors need to be invoiced at a later date. Otherwise, invoice all community-specific sponsors after the interns have accepted the internship. We don't want to invoice a sponsor and then have the intern not accept the internship and have to credit the community. General funding sponsors can be invoiced at any time.

Ask Software Freedom Conservancy to invoice the sponsor, and they will send the invoice. Instructions for the format and email address to send to are in the GitLab notes repository in the `payment-emails.txt` file and `email/email-sponsor-confirmation.txt`. Mark the invoice as sent in Invoice Ninja when you make the invoice request. Mark in the invoice private notes the date you sent the invoice request. Once Conservancy sends the invoice, update the sent and due date to reflect the actual invoice dates.

Conservancy does not update their request tracker ticket with when the invoice has been paid. Sometime during the year, they will update their ledger file to indicate when the invoice has been paid. The ledger file is in `Ledger/outreachy.ledger`. You can use this command to look at the accounts receivable entries in ledger: `ledger -V -f Ledger/outreachy.ledger --group-by date register /^Accrued:Accounts\ Receivable/` 

Once the ledger shows the invoice amount as a negative amount in Accrued:Accounts Receivable:Outreachy, it means Conservancy has recorded the invoice as paid. Once the invoice shows up in ledger as being paid, then enter payment for the invoice in Invoice Ninja for that specific date in ledger.

# Intern agreements

Conservancy needs to get sent the signed intern agreements. They use a JSON file exported from the Outreachy website to automatically generate request tickets for the intern's tax, payment, and stipend tickets. You can export the JSON file from the [Outreachy dashboard](https://www.outreachy.org/dashboard/) once all interns have signed the contracts.

The email draft format for sending the contracts in the private GitLab repository, in the file email/email-intern-signed-contracts-to-sfc.txt

# Intern chats

The chat schedule is here: https://www.outreachy.org/docs/internship/#chats

Chats take place on the #chat stream as a new topic with the following naming scheme: `[Month and year their internship started, which is either May YYYY or Dec YYYY] - [Week number] - [Name of the topic]` (if you don't know how to create a new topic on Zulip, see [Start a new topic](https://zulipchat.com/help/start-a-new-topic)). They are typically announced a week before the scheduled date, reminding interns, mentors and alums of the date and time it will happen (always in UTC) as well as a brief description of what will be discussed that day.

As interns gain more confidence throughout the internship, they may start the chat themselves by talking about their own experiences with the topic of the day, but sometimes they'll need a bit of encouragement to start replying. If needed, start the chat by asking them a couple of questions, or by answering the prompt yourself — this will help them structure their own replies.

When running the chats, give about 2-5 minutes between asking a question and expecting a response from anyone. Zulip doesn't show when people are typing, so give people some time to compose. Most people tend to send a couple larger paragraphs, which takes some time to type.

The most important part of the chats is to engage the interns. Ask questions or get them to provide more details. Talk about similarities with their experiences to other intern experiences, or your own experiences.


If the conversation gets off topic, it's okay! That usually means the off-topic thing is interesting to many people.

Some interns are more shy than others. They'll lurk in the channel while the chat is going on. I try to engage them by asking an open-ended question. Usually the question is related to the topic at hand. So if we're talking about struggling during the internship, I might ask them what kinds of internship tasks or topics took more time during the last few weeks.

Near the end of the chat, I say, "I want to make sure we can hear from some of the quieter voices." And then I'll @ the people who haven't said anything this whole time. I keep a list of interns who have interacted, mostly in my head, sometimes in a text file.

Chats typically take 1 hour.

# Intern feedback

To mark all interns with successful mid-point feedback as being authorized payment:

```
>>> from home import models
>>> current_round = models.RoundPage.objects.get(internstarts='2019-12-03')
>>> interns = models.InternSelection.objects.filter(applicant__application_round=current_round, midpointmentorfeedback__payment_approved=True, midpointmentorfeedback__extension_date__isnull=True)
>>> len(interns) # make sure this matches the number of interns you say you're paying in the email
>>> for i in interns:
...     i.midpointmentorfeedback.organizer_payment_approved = True
...     i.midpointmentorfeedback.save()
... 
>>>

# Career Chats

Each round, we have three opportunities to get Outreachy interns to think about career opportunities:

 - Week 10 - intern chat about career opportunities
 - Week 11 - informal chats assignment in biweekly blog post/assignments email
 - Week 12 - intern chat - networking / informal chats

The chat about career opportunities makes interns realize how important networking is to get a job. We then prompt them to schedule 2 to 3 informal chats with someone who contributes to open source or is paid to work on open source. During week 12, we talk about tips for approaching people for an informal chat and tips for getting the most out of the chats.

As part of this, we provide interns with a list of people they can contact for an informal chat. The list is made up of past/current Outreachy mentors/coordinators, alums, and employees of current Outreachy sponsors who are paid to work on open source. Interns can opt into which people they contact (or contact someone completely different).

Organizers will need to send an email to sponsors, seeking employees of the sponsors who are paid to contribute to open source, who can volunteer to have an informal chat with an Outreachy intern. The email template is in the private Outreachy organizer repo under the filename email/sponsor-invite-informal-career-chat.txt

Sponsor emails are generally in the Client tab of Invoice Ninja, but there may be additional contacts that Sage knows about. Ping them.

## Week 10: Career opportunities

Questions to get the discussion moving:
 - For current interns, alums, and mentors: What are all the ways you can think of to move your career forward? (There is no wrong answer.)
   - networking
   - Networking and referrals are so important! Between 50% to 80% of jobs go unlisted. The jobs are filled by someone the team knows: https://www.collegerecruiter.com/blog/2013/03/28/80-of-job-openings-are-unadvertised/
   - formal education (university)
   - coding schools
   - school career counselors
   - online tutorials
   - FreeCodeCamp - https://www.freecodecamp.org
   - certifications
   - Red Hat has free online courses at https://www.redhat.com/en/services/training-and-certification?learning_options=free_courses and at https://www.edx.org/school/red-hat
   - work on resume and cover letter
   - LinkedIn recommendations
   - find out what skills are in job postings and learn those skills
   - contribute to open source
   - have a portfolio
   - blogging
   - consulting work
   - conferences
   - local meetups
   - Online Slack groups often have a "jobs" channel. I hang out in the LGBTQ in Tech slack (for queer folks): https://lgbtq.technology/ I used to hang out more in the Women in Tech chat before I came out as non-binary: https://witchat.github.io/ Feel free to share a link to other online forums for marginalized groups in tech.
   - other paid "summer of code" programs: https://github.com/tapaswenipathak/Open-Source-Programs
   - look at which companies sponsor open source conferences, or your open source community. For example, LWN.net publishes which companies are the top Linux kernel contributors (e.g. https://lwn.net/Articles/821813/). For OpenStack the statistics are https://www.stackalytics.com/ You can use these lists of sponsors to identify companies that participate the most and they are probably hiring.
   - some open source communities have a jobs board, e.g. https://www.python.org/jobs/
   - There is a monthly Y Combinator thread on "Who's hiring?" and some "Seeking Freelancer" threads. These are interesting for finding new jobs or contract work. Some of it is remote work and/or open source. For example, the January 2020 links: https://news.ycombinator.com/item?id=21936439 and https://news.ycombinator.com/item?id=21936440
 - For current interns, in emoji scale: Rate 1-10 how comfortable you feel asking your mentor for help? 1 is the least comfortable. 10 is that you're 100% comfortable and happy to ask.
   - wait for answers
   - It's okay to have to work your way up to asking your mentor for help. Many people start out being shy (like me!) and work their way up to feeling more comfortable asking for career advice.
   - I've found that sometimes people have no problem asking a mentor for advice on coding, but then don't feel as comfortable saying " In the future I’d like to work at XYZ organization, do you have any advice?" and that is something important.

```
A lot of people think a job search is like this:
See job >> apply for job >> organization reviews resumes submitted >> organization calls the best qualified >> interview

When really it’s more like this:
See job>> ask mentor if they know someone >> talk to 1-2 people who work there to get information >> they refer you to the hiring manager >> get called in for an interview
```

```
A good piece of advice from our former career advisor:

'For me, even if you're not looking for a job today finding companies/organizations you want to work for is a win. It's the easiest time to ask for an informational chat with someone. A script like: "I'm currently an intern and I see myself working at XYZ, would it be ok if I emailed with some questions? I'd love to get some advice?" can work wonders for getting you information, and it increases the amount of people in your network.

Especially in the open source community, knowledge is power, and just knowing that an organization screens github before they look at resumes or if they're really focused on documentation can allow you to tailor your resume, and speak to different things in interviews...or identify companies you wouldn't want to work for.'
```

```
A good piece of advice from an Outreachy mentor:

'I recommend letting your mentor know that you will be looking for jobs so they can send you job openings ("I will be looking for jobs after my internship. Are there any job openings you think might be a good fit for me?"). Don't be afraid to ask them for advice or review your resume. Maybe they can introduce you to people.

There is no harm in asking them although it might feel awkward if you're not used to it :). Many of us are afraid that this is self-promotion and we don't like to do it, but your mentor is probably happy to help you!'
```

# Week 12: Informal chats


An informal chat is a conversation with another person. It can be as simple as trying to answer one question.

For interns, mentors, and alums: Have you ever had a talk (with a professor, or family member) where you had a goal or something you wanted to talk about?

For me, my spouse and I have a weekly "check in" meeting. We talk about how our relationship is doing, what our schedule looks like for the week, and we make a grocery list.


When I was a student, I never wanted to talk to professors outside of class. I felt ashamed if I had to ask questions during office hours. But a fellow classmate encouraged me to go to office hours. They said that part of the professor's job was to answer questions.

In fact, they hung out in a computer science professor's office all the time! They talked to the professor about student projects and interesting new software. In turn, the professor shared information about research opportunities, talked about interesting software, and connected them to people in open source communities.

I wish I had connected to professors in a more informal way. I also wish I had done more informal chats with my co-workers when I worked at Intel. I was so focused on doing my work that I didn't spend as much time networking. And I think it would have helped my career to network more.


What are other people's stories about talking to a professor, family member, or friend with a particular goal in mind?


```
I worry because sometimes people build up these conversations of "this is your ONE CHANCE to talk to this person" when really sometimes having a small informal conversation can make a difference in getting information.
```

We've seen in other chats that many people find jobs through networking. One technique is when you see a job posting, think of everyone you know who works at that company or organization. Then ask those contacts:

"What's it like working there?"
"Do you know anyone who works on that team?"
"I'm thinking of applying, is there anything I should know?"
"Do you have any tips if I get called in for an interview?"
"Is there anything I should know?"

---

For mentors, alums, and interns: If you had to ask someone do an informal chat, how would you feel about? Add an emoji that expresses your reaction.

Okay, now I want everyone to imagine this scenario. You've landed your dream job. It was challenging to get hired, but the team you're working with is amazing.

After a year, someone you know contacts you and says: "I'm thinking about applying to your company. What's it like working there? Can we chat about it?"

Add an emoji that expresses your feelings about them asking to talk to you.

---


I know asking for an informal chat can seem intimidating. What are people's concerns?


Sometimes we get anxious about talking to people. We imagine how awful it could be. But, it's helpful to ask ourselves two questions:

 - What's the worst that could happen?
 - How likely is it to happen?

I think the worst thing that has happened to me is not getting an email back. And I can't assume why someone didn't email me back. They could be busy that week. I think we like to jump to the worst case scenario when someone doesn't answer back.

Also, sometimes people just don't see your message. A lot of people only log in to LinkedIn every couple months. Or your message gets lost in a lot of other social media notifications.

If you approach someone via email, and you don't get a reply within a week or two, don't feel shy to send one ping. As long as you're not sending a ping after one day, and you're friendly about it ("Hey, I sent you this email two weeks ago, and I'm still super interested in your answers!"), people usually don't mind.


And if the person you approach for an informational chat is really busy, sometimes that advice is "read this blog post" or "here's the link to the applicant guide". Even if you approach someone for a conversation, and they just send you resources, that's still very useful.


Sometimes we convince ourselves that people are going to be rude to us. But then it turns out to not be true! Other times, people are blunt or rude when saying no. It's important to recognize that is hurtful, and also that means we need to find people who are more encouraging.

It can be helpful to ask your mentor to connect you to people you want to have an informal chat with. Having a mentor who is experienced and a respected community member can mean the other person is more willing to talk, or they're nicer about saying no. Also, your mentor is often better at describing your work and role in a positive way! So do ask your mentor to provide an introduction if they have a connection to the person you want to do an informal interview with.


If you're approaching a stranger, do your research first! The goal is ask specific questions that won't take up too much time. Try to ask questions that aren't public, like what the company culture feels like as an employee.


I've also had people say, "Can I email you a list of questions?" after I say I don't have time for a video chat. That helps, since I maybe don't have mental bandwidth to talk on the phone. If you do send questions, keep the list short, like 3-5 questions.


If asking someone via chat (when you might feel more pressure for them to respond sooner) is too much, then maybe starting with an email. Or maybe it's you starting in IRC and saying "I'd love to ask you 1-2 specific questions that might help my career, but I want to be respectful of your time, can I email them to you so you can get back on your schedule?"


One thing I want to bring up is that in these conversations it's ok (and sometimes useful) to say "I don't know something" so saying to someone "I’ve never heard of that. How does that work? " does not make you look bad but is a great conversation starter



Make sure to send a thank you email to people you do an informal chat with! You're asking them for their time, and sending a thank you email can help them remember you later. If the person sends you a follow up email later,



# Week 14: Wrap up chat

 - For Outreachy interns and alums: What have/did you learned about yourself during your Outreachy internship? Is working remotely easy or hard for you? Do you like working on many smaller tasks or one big task? Are you good at debugging, writing documentation, developing new features, etc?
   - Thinking about what you liked and what you found hard about your internship will allow you to apply for jobs that contain more of the fun stuff and less of the difficult stuff :). It will help you find a career that is fulfilling.
