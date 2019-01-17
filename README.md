# <img src="http://www.rice.edu/_images/rice-logo.jpg" width=180> Comp427, Spring 2018, Homework 1

## Rational Paranoia

The homework specifications, as well as the corresponding course slide decks,
can be found on the [Comp427 Piazza](https://piazza.com/class/jqifhp864b37ju).
This assignment is due **Thursday, January 17 at 6 p.m.**

You will do this homework by editing the _README.md_ file. It's in
[MarkDown format](https://guides.github.com/features/mastering-markdown/)
and will be rendered to beautiful HTML when you visit your GitHub repo.

## Student Information

Please also edit _README.md_ and replace your instructor's name and NetID with your own:

_Student name_: Arthur Chen

_Student NetID_: ac99

Your NetID is typically your initials and a numeric digit. That's
what we need here.

_If you contacted us in advance and we approved a late submission,
please cut-and-paste the text from that email here._

## Problem 1

- Scenario: {Stadium}
- Assumptions:
  - This football stadium frequently is completely filled for football games and its only secondary use is for team practice.
- Assets:
  - Players and Sports Staff
    - In my opinion the players and staff are the most important assets to protect. Without the players and staff, there would be no fans or security staff. Then, without the fans there would be no need for infrastructure.
  - Fans
    - If fans felt unsafe or unprotected during events, then fewer people would attend games. Fans also generate revenue for sports organizations, so without fans there would be no money. Therefore, I need to protect my fans in order for them to attend my events such that I can make money.
  - Infrastructure
    - Infrastructure -- stadium, seats, parking lot, steps -- are all vital to giving the fans an enjoyable experience. Therefore, if the infrastructure was damaged/destroyed, it needs to be replaced/repaired. This costs money, so it should be protected by the security staff that can also protect the fans/players/staff at the same time.
  - Security Staff
    - Security needs to be able to protect itself because this ability also allows the security to protect others. Also, even though one could replace security relatively easily, it's unethical to just allow your security to get injured and replace them.
- Threats:
  - Intruders
  - You need to protect everyone inside of the stadium from outside intruders because those are the people that can cause the most harm. These are the people that can bring guns or bombs and potentially kill hundreds of people.
  - Fans
  - Now assume that a fan has passed by the initial screening of weapons. This fan is still able to hurt the surrounding people without any tools. So, you need to be able to stop them
  - Players
  - Since this is a sporting event -- competition -- players will get riled up. Eventually, this could result in an outburst where players end up fighting each other. You need an outside source to de-escalate this fight and protect both team’s players, because the players are vital to both organization’s success.
- Countermeasures:
  - Security Staff
  - A security staff is needed to physically prevent intruders from getting in, fans from hurting either players or other fans, and players from hurting other players. A security could be extremely efficient and preventing all these potential problems based on their organization and equipment. Security, that protects the outside of the stadium could be equipped with tasers and pepper spray, and possibly hidden firearms. There could also be a stockpile of stronger(?) firepower in the stadium. These weapons could be used to defend all types of intruders from belligerent drunk people to people fully equipped people with firearms. The security inside could be unarmed, but able to physically break up any type of fight/brawl/altercation. This security staff would also be able prevent intruders from entering the stadium past its open hours, like in the middle of the night. Security staff would also be present during team practice. Then the cost of this security staff in, I assume, all places would be extremely low, especially in comparison to how much money team owners make. A single worker at most makes twenty dollars an hour, and that is easily payable for a team owner.
  - Surveillance System
  - Surveillance would be used to monitor the stadium to ensure nobody is tampering with any infrastructure or hurting other people. The surveillance system would also allow the management to have video recorded evidence of any type of fight/altercation that can be used in like legal side of things. The cost of the surveillance system is just the initial investment to get it set up/working. The cost for maintenance cannot be too expensive. Again, team owners make hundreds of MILLIONS of dollars.

## Problem 2

- Scenario: {Grading}
- Assumptions:
  - I am the same person I am now, and I’m grading a class at Rice University. Some of my students could have mental breakdowns and try hurt me.
- Assets:
  - Grades
  - I need to protect the grades from other students because it is an invasion of privacy. If other students were able to find the grades of another student that could be an honor code policy. A student could use another student’s low grades to bully them, and I would not want that.
  - Homework Assignments
  - I need to protect the homework assignments themselves because I need to prevent students from cheating. Students could either go back and change their answers or use another student’s answers to do their own homework. Nevertheless, both options are a form of cheating and an honor code violation.
  - MYSELF
  - What, if I give a student a bad grade, and they have a mental breakdown and try to physically hurt me. What if they start threatening me? I need to protect myself because I love myself and my below-average mental health.
- Threats:
  - Stealing
  - I need to make sure students do not somehow physically steal the homework assignments/whatever I use to grade assignments, such that they do not cheat. This includes chaning their own answers or other people's answers
  - C Y B E R (?) Attacks
  - I need to make sure students do not somehow hack into my laptop and change the grades digitally. This would be unfair to other student's that are actually putting in the work.
  - PHYSICAL attacks
  - I cannot let these YOUNGLINGS physically BULLY me. I love myself and would not like to be in physical or mental pain.
- Countermeasures:
  - Passwords
  - Passwords are free. There is no way that a college, computer science major student can somehow break into my laptop. Especially, when my password is some dumb, long phrase, which has no relevance to me at all. I also need to train my mind to not fall victim to email phishing schemes.
  - Two-way confirmation
  - Now let’s say they physically steal my laptop, take out the hard-drive and go to Walmart to pull the data out of it. If I were to only store my grades behind a second layer of protection – Canvas – then this would be pointless. Passwords are free, and so is my creativity for passwords.
  - PHYSICAL TRAINING
  - Now, if the younglings were to physically attack me, and I have trained in some random martial art, I can possibly win. However, I do not have the time or the money or the energy or the mental-willpower to train in some martial art to defend myself from angry computer science students. So, I could not justify this type of counter measure for me, but this counter measure could work for a more energetic grader.

## Problem 3

- Scenario: You are protecting a database from users
- Assumptions:
  - You are only protecting the database from the online perspective, meaning you do not have to protect the physical servers of database. You also can assume that you do not have to protect adversaries from physically/in person using your computer to access the database with full admin privileges. You are protecting an SQL database.
- Assets:
  - Tables/Collections themselves
  - Tables and collections are the containers to hold all data to make some service work. Therefore, we need to protect these containers because if they were mutated or deleted, the service itself can break.
  - Rows/Documents themselves
  - Rows and documents are containers to hold individual data pertaining to a specific key. If the rows/documents themselves were deleted completely, then the service itself could not portray any information to the user. Another aspect to look at is what happens if the data inside a row/document is mutated? This could lead to the service portraying falsified information to the user, making them lead to incorrect assumptions or conclusions. Finally, we also want to make sure that the user uploaded that is not corrupted with malware.
  - User logins
  - User logins need to be protected because with access to another user’s login, you can access all data found under their user. Also, what if this user uses the same login for a different website, then you could possibly use a single login to access several different locations.
- Threats:

  - SQL Injections
  - SQL injections covers such a broad spectrum of different topics. Specifically, we need to protect SQL injections that can: drop/add tables, drop/add rows, mutate data found in rows.
  - Malware Injections
  - We need to make sure that uploaded does not contain malware because this data could be distributed to anyone that pulls the data locally.
  - Phishing Scams
    - Phishing scams to gain access to employee privileges, which could allow remote user's to create their own employee privileges.

- Countermeasures:
  - Buying good computer scientists that can do the following:
  - Create endpoints or stored procedures such that users are never really running “dynamic” queries. In reality, users are just supplying keys or identifiers to find specific data.
  - Set restrictions on all levels of user privileges. This means that there are levels of access to databases. For example, unauthorized users cannot read or write data from databases. Then, authorized users can only run stored procedures or defined endpoints that can only do one thing. Then, for workers we can restrict their access based on their job description. For example, let’s say a bank employee has the role to change phone-numbers tied to an account, well they should not be able to also change the balance of a person.
  - Monitor database activity and usage in order to detect data leakage, unauthorized transactions, and system attacks. For example, you don’t want people to automate a way to upload or pull millions of data points at once, like what happened with the bots for Twitter.
  - Prevent SQL Injections/Malware Injections – honestly I do not know how to stop these, but I hope the good computer scientists that I hire can prevent these.
  - Training employees from installing malware or falling victim to schemes. Specifically, I believe a lot of hacking requires an initial breach or start point in order to really succeed. Usually it is pretty hard to discover a person’s password, but by making them download programs through bait emails, a hacker can have direct access to a person’s computer. Then, I imagine you can do a bunch of stuff that I am not well-versed on.
