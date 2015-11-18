Nelia Bennett
ISYS 0475
Assignment #02

Apache SpamAssassin Project
Apache SpamAssassin is a server based open-source anti-spam platform which gives webserver system administrators a filtering tool to classify email and block unsolicited bulk email, spam.  
Unsolicited bulk email, spam, is the process of flooding the Internet with mass copies of the same message that attempts to force the message on recipient who normally not choose to receive such messages.  Spam is normally commercial advertising for questionable products, get-rich-quick schemes, sexual related products / relationships, etc.  Most of the cost associated with spam are paid for by the carrier or recipients and actually cost the senders very little.
To classify and / or block spam, SpamAssassin uses a scoring framework and plugins.  It also uses advanced heuristic and statistical test.  These tests are performed on the email headers, the message body text and also uses Bayesian filtering, DNS blocklists and collaborative filtering databases to eliminate spam messages.
Apache SpamAssassin is a project of the Apache Software Foundation (ASF).
Everyone that participates in the development project, SpamAssassin, does so on a volunteer basis.  The project uses volunteers to help improve the documentation, to improve its accuracy, completeness and its clarity.
ASF uses volunteers to make code contributions such as patches, code, Perl, regression, write new rules and add rules written by others.  Coders must submit a Contributor License Agreement before any code before can be accepted.  This license agreement defines the terms under which intellectual property has been contributed to the ASF and allows them to defend the project in case of a legal dispute regarding the software some future time.  Coders can login to Bugzilla and look for bugs that need to be fixed.
New rules are checked into SVN in a developer's sandbox and will be picked up for testing in two ways.  First, the PreflightBuildBot will pick up the new rule and run a set of mass-checks against its own corpus, along with any other sandbox rules.  Second, that night, the NightlyMassCheck will take place and several people will run it against *their* corpora along with the entire SA ruleset.  The results of both test can be viewed at the RuleQaApp.
People can find information about the Spam Assassin Project at http://spamassassin.apache.org.  At this website they will find a significant amount information under the menu options News, Wiki, Download, FAQ (Wiki), Docs, Mailing Lists (Wiki), Bugs (Bugzilla) and Credits (SVN).
From me research on the subject, it is quite apparent that the SpamAssassin Project is in serious need of and is actively search for new volunteers to  help with the project.
