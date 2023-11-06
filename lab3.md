# Lab Report 3 - Bugs and Commands

## Part 1 - Bugs


## Part 2 - Researching Commands


The *Grep* command 

### Command-line options: 


## -i: Case Insensitive Search 

I found this command-line option from the class lecture slides on Canvas. 

Example 1:

```grep -i "threat" ./technical/911report/chapter-8.txt```


` THE SUMMER OF THREAT
reports about threats. Indeed, there appeared to be possible threats almost
To understand how the escalation in threat reporting was handled in the summer of
2001, it is useful to understand how threat information in general is collected and
disseminated to state and local law enforcement agencies. Threat reporting must be
disseminated, either through individual reports or through threat advisories. Such
advisories, intended to alert their recipients, may address a specific threat or be
                Central Intelligence GeorgeTenet was briefed regularly regarding threats and other
                reporting on terrorist threats and planned attacks increased dramatically to its
                community disseminated a terrorist threat advisory, indicating a heightened threat
            In response to these threats, the FBI sent a message to all its field offices on
                that there was a domestic threat.
                Qaeda policy on April 30, they began with a briefing on the threat.
                by the CIA on May 15 regarding al Qaeda generally and the current threat reporting
                threats to attack America and American interests, the specific threats mentioned in
                Center (CTC) Chief Cofer Black told Rice that the current threat level was a 7 on a
            Threat reports surged in June and July, reaching an even higher peak of urgency. The
                summer threats seemed to be focused on Saudi Arabia, Israel, Bahrain, Kuwait, Yemen,
            That same day, the State Department notified all embassies of the terrorist threat
            A terrorist threat advisory distributed in late June indicated a high probability of
                Associates Making Near-Term Threats." The latter reported multiple attacks planned
            On June 21, near the height of the threat reporting, U.S. Central Command raised the
                state and local law enforcement agencies summarizing information regarding threats
                from Bin Ladin. It warned that there was an increased volume of threat reporting,
                further stated, "The FBI has no information indicating a credible threat of
                that the July 4 holiday might heighten the threats. The report asked recipients
                worked with senior officials in the Gulf. In late July, because of threats, Italy
                the CIA, and the FBI met with Clarke to discuss the current threat. Attendees report
                that they were told not to disseminate the threat information they received at the
            That same day, the CIA briefed Attorney General Ashcroft on the al Qaeda threat,
                little additional warning could be expected. The briefing addressed only threats
                the "current threat level" in the United States. They were told that not only the
                threat reports from abroad but also the recent convictions in the East Africa
                mentioned was the need, in light of increased threat reporting, to have evidence
                CSG discussion was still the al Qaeda threat, and it included mention of suspected
                convinced. Some asked whether all these threats might just be deception. On June 30,
                the SEIB contained an article titled "Bin Ladin Threats Are Real." Yet Hadley told
                threat reporting and the upcoming anniversary of the East Africa embassy bombings,
            On August 3, the intelligence community issued an advisory concluding that the threat
                of impending al Qaeda attacks would likely continue indefinitely. Citing threats in
                his briefers whether any of the threats pointed to the United States. Reflecting on
                threat of a Bin Ladin attack in the United States remained both current and
                in New York, the threat phoned in to the embassy, or the fact that the FBI had
                We have not been able to corroborate some of the more sensational threat
            No CSG or other NSC meeting was held to discuss the possible threat of a strike in
                President and his top advisers of the possibility of a threat of an al Qaeda attack
                any discussions with the President of the domestic threat during this period.
                and severity of threat reports were unprecedented. Many officials told us that they
                their large number, the threats received contained few specifics regarding time,
                overseas; others indicated threats against unspecified "U.S. interests." We cannot
            Government Response to the Threats
                were the NSC's bridge between foreign and domestic threats.
                threats. Numerous actions were taken overseas to disrupt possible attacks- enlisting
                because to the extent that specifics did exist, they pertained to threats overseas.
                As noted earlier, a threat against the embassy in Yemen quickly resulted in its
                closing. Possible domestic threats were more vague. When reports did not specify
                FBI threat advisories made this point.
            His analysis, however, was based not on new threat reporting but on past experience.
            The September 11 attacks fell into the void between the foreign and domestic threats.
                The foreign intelligence agencies were watching overseas, alert to foreign threats
                domestic threat from sleeper cells within the United States. No one was looking for
                a foreign threat to domestic targets. The threat that was coming was not from
                tell the agencies how to respond to the threats. He noted that the agencies that
                experience with such threats and had a "playbook." In contrast, the domestic
                the domestic agencies. The briefing focused on overseas threats. The domestic
                agencies were not questioned about how they planned to address the threat and were
                a CD-ROM to air carriers and airport authorities describing the increased threat to
                of these briefings discussed the hijacking threat overseas. None discussed the
                threat within the United States and did not order surveillance of suspected
                he mentioned the heightened terrorist threat in individual calls with the special
                us the threat information was "nebulous." He wished he had known more. He wished he
                had had "500 analysts looking at Usama Bin Ladin threat information instead of
                in Pickard's briefings about the terrorist threat situation. Pickard told us that
                threats anymore. Ashcroft denies Pickard's charge. Pickard says he continued to
                although the reports of threats were related to overseas targets. Ashcroft said he
                doing in response to the threats and did not task it to take any specific action. He
            In sum, the domestic agencies never mobilized in response to the threat. They did not
                against a domestic threat.
            By mid-May 2001, as the threat reports were surging, a CIA official detailed to the
                    will stand behind their decisions then, especially since the biggest threat to
                the threat reporting during the summer of 2001.
                hijacking threat might have derailed the plot.107With time, the search for Mihdhar
                respond to the threats.
                his or her in-box to the threat reports agitating senior officials and being briefed`

  In this example, the `grep` command is searching for the string "threat" in the file 
  *chapter-8.txt* under the `/911report` directory. It's using the `-i` option, which is 
  case insensitive search, so the `grep` command is matching the string "threat" in the
  file, while ignoring the cases of the characters. In other words, "THREAT" and "threat"
  are represented the same way. This command-line option is useful because it searches for 
  a specific string that you are looking for in a file or files where the cases of those characters, 
  whether it's upper or lowercase, don't have to match. 



Example 2:

```grep -i "Alcohol" ./technical/government/Alcohol_Problems/*```

`./technical/government/Alcohol_Problems/DraftRecom-PDF.txt:address the full spectrum of alcohol problems among ED
./technical/government/Alcohol_Problems/DraftRecom-PDF.txt:"alcohol problems" does not always include risky drinking and
./technical/government/Alcohol_Problems/DraftRecom-PDF.txt:detail on the spectrum of alcohol problems. He suggested the main
./technical/government/Alcohol_Problems/DraftRecom-PDF.txt:include the whole continuum of alcohol problems, not just a portion
./technical/government/Alcohol_Problems/DraftRecom-PDF.txt:of the continuum such as alcohol-dependent drinkers.
./technical/government/Alcohol_Problems/DraftRecom-PDF.txt:of alcohol problems" include primary prevention. She recommended
./technical/government/Alcohol_Problems/DraftRecom-PDF.txt:Carl Soderstrom wondered whether "alcohol problems" referred to
./technical/government/Alcohol_Problems/DraftRecom-PDF.txt:problems in addition to medical problems. The phrase "alcohol
./technical/government/Alcohol_Problems/DraftRecom-PDF.txt:"in the emergency setting" because alcohol problems are not limited
./technical/government/Alcohol_Problems/DraftRecom-PDF.txt:to patients. Perhaps the recommendations should address alcohol
./technical/government/Alcohol_Problems/DraftRecom-PDF.txt:Stephen Hargarten thought that the term "alcohol-related
./technical/government/Alcohol_Problems/DraftRecom-PDF.txt:problems" would appeal to clinicians more than "alcohol problems"
./technical/government/Alcohol_Problems/DraftRecom-PDF.txt:Richard Ries said he did not believe that screening for alcohol
./technical/government/Alcohol_Problems/DraftRecom-PDF.txt:alcohol use disorders or problems, not for medical care
./technical/government/Alcohol_Problems/DraftRecom-PDF.txt:people with severe alcohol problems and alcohol dependence than did
./technical/government/Alcohol_Problems/DraftRecom-PDF.txt:Richard Longabaugh said that the term "alcohol problems" implies
./technical/government/Alcohol_Problems/DraftRecom-PDF.txt:"alcohol-related problems" because consumption is not the problem.
./technical/government/Alcohol_Problems/DraftRecom-PDF.txt:Li added his support to "alcohol-related problems," but
./technical/government/Alcohol_Problems/DraftRecom-PDF.txt:in mind, he suggested listing the full spectrum of alcohol
./technical/government/Alcohol_Problems/DraftRecom-PDF.txt:problems, from risky drinking to alcohol abuse to alcohol
./technical/government/Alcohol_Problems/DraftRecom-PDF.txt:would be to say, "the full spectrum of alcohol misuse."
./technical/government/Alcohol_Problems/DraftRecom-PDF.txt:"Problematic alcohol-use screening instruments under consideration
./technical/government/Alcohol_Problems/DraftRecom-PDF.txt:that provide alcohol-use interventions for patients to decrease
./technical/government/Alcohol_Problems/DraftRecom-PDF.txt:that screening activities for alcohol problems should be integrated
./technical/government/Alcohol_Problems/DraftRecom-PDF.txt:Smith returned to the idea of linking alcohol interventions with
./technical/government/Alcohol_Problems/DraftRecom-PDF.txt:Pollock asked Gordon whether research on alcohol interventions
./technical/government/Alcohol_Problems/DraftRecom-PDF.txt:issues on screening and interventions for alcohol problems among ED
./technical/government/Alcohol_Problems/DraftRecom-PDF.txt:addresses. He noted that alcohol screening in the ED is currently
./technical/government/Alcohol_Problems/DraftRecom-PDF.txt:interventions for alcohol problems.
./technical/government/Alcohol_Problems/DraftRecom-PDF.txt:needed to institutionalize screening and intervention for alcohol
./technical/government/Alcohol_Problems/DraftRecom-PDF.txt:organizational issues-from the structure of alcohol and screening
./technical/government/Alcohol_Problems/DraftRecom-PDF.txt:care outcomes and recidivism, rather than alcohol use outcomes.
./technical/government/Alcohol_Problems/DraftRecom-PDF.txt:sooner patients with alcohol problems can receive help. She noted
./technical/government/Alcohol_Problems/DraftRecom-PDF.txt:is appropriate for alcohol problems because they are not just
./technical/government/Alcohol_Problems/DraftRecom-PDF.txt:department in the overall picture of treating alcohol problems.
./technical/government/Alcohol_Problems/DraftRecom-PDF.txt:Bernstein noted that alcohol-dependent patients clearly need
./technical/government/Alcohol_Problems/DraftRecom-PDF.txt:with alcohol problems.
./technical/government/Alcohol_Problems/DraftRecom-PDF.txt:intervention for alcohol problems among ED patients.
./technical/government/Alcohol_Problems/DraftRecom-PDF.txt:screening and interventions for alcohol problems among ED patients
./technical/government/Alcohol_Problems/DraftRecom-PDF.txt:from alcohol problems.
./technical/government/Alcohol_Problems/DraftRecom-PDF.txt:to make research on alcohol problems in the ED a high priority.
./technical/government/Alcohol_Problems/DraftRecom-PDF.txt:prevalence of alcohol problems among ED patients makes it worthy of
./technical/government/Alcohol_Problems/DraftRecom-PDF.txt:believed that data on the prevalence and severity of alcohol
./technical/government/Alcohol_Problems/DraftRecom-PDF.txt:patients affected by alcohol problems and the significant health
./technical/government/Alcohol_Problems/DraftRecom-PDF.txt:many patients with alcohol problems as the psychiatry or family
./technical/government/Alcohol_Problems/DraftRecom-PDF.txt:become research priorities. Alcohol and injury, as well as brief
./technical/government/Alcohol_Problems/DraftRecom-PDF.txt:thought combining alcohol and drug research in EDs could lead to
./technical/government/Alcohol_Problems/DraftRecom-PDF.txt:importance of screening for alcohol and other drugs together. To
./technical/government/Alcohol_Problems/DraftRecom-PDF.txt:dealing with alcohol problems is an integral part of their job.
./technical/government/Alcohol_Problems/DraftRecom-PDF.txt:Research on alcohol problems is as important as research on sepsis
./technical/government/Alcohol_Problems/DraftRecom-PDF.txt:alcohol-related research in the surgery section. It was all in the
./technical/government/Alcohol_Problems/DraftRecom-PDF.txt:alcohol section, which surgeons do not explore. If we want surgeons
./technical/government/Alcohol_Problems/DraftRecom-PDF.txt:objective to reduce alcohol-related injury and ED visits by 15%
./technical/government/Alcohol_Problems/DraftRecom-PDF.txt:pharmocotherapy for patients with alcohol-related problems in the
./technical/government/Alcohol_Problems/Session2-PDF.txt:Identifying ED Patients with Alcohol Problems
./technical/government/Alcohol_Problems/Session2-PDF.txt:Many patients in the emergency department (ED) have alcohol
./technical/government/Alcohol_Problems/Session2-PDF.txt:further examine and refine alcohol-screening questionnaires in the
./technical/government/Alcohol_Problems/Session2-PDF.txt:Alcohol problems defined
./technical/government/Alcohol_Problems/Session2-PDF.txt:Alcohol problems designate a spectrum from risk behavior to
./technical/government/Alcohol_Problems/Session2-PDF.txt:illness, and from problematic consumption to alcohol use disorder.
./technical/government/Alcohol_Problems/Session2-PDF.txt:screening for several alcohol endpoints. Acute intoxication is of
./technical/government/Alcohol_Problems/Session2-PDF.txt:certainly be considered an "alcohol problem." The blood or breath
./technical/government/Alcohol_Problems/Session2-PDF.txt:alcohol concentration (BAC), coupled with our clinical
./technical/government/Alcohol_Problems/Session2-PDF.txt:observations, may help us identify intoxication. Most alcohol
./technical/government/Alcohol_Problems/Session2-PDF.txt:screening tests identify patients with alcohol use disorders or
./technical/government/Alcohol_Problems/Session2-PDF.txt:problematic consumption of alcohol. The American Psychiatric
./technical/government/Alcohol_Problems/Session2-PDF.txt:(ICD-9, -10) have rigorously defined alcohol abuse and alcohol
./technical/government/Alcohol_Problems/Session2-PDF.txt:cases of alcohol abuse meet the ICD-10 definition. In general, an
./technical/government/Alcohol_Problems/Session2-PDF.txt:alcohol use disorder is present when an aspect of the patient's
./technical/government/Alcohol_Problems/Session2-PDF.txt:by alcohol. Before function is compromised, problematic
./technical/government/Alcohol_Problems/Session2-PDF.txt:toward identifying patients with high alcohol consumption before
./technical/government/Alcohol_Problems/Session2-PDF.txt:Institute on Alcohol Abuse and Alcoholism (NIAAA) defines at-risk
./technical/government/Alcohol_Problems/Session2-PDF.txt:the alcohol use spectrum. However, real tests don't perform
./technical/government/Alcohol_Problems/Session2-PDF.txt:would address both current and lifetime alcohol problems. Current
./technical/government/Alcohol_Problems/Session2-PDF.txt:identifying alcohol use disorders or problematic consumption.7 Of
./technical/government/Alcohol_Problems/Session2-PDF.txt:course, BAC can help identify acute intoxication. The alcohol
./technical/government/Alcohol_Problems/Session2-PDF.txt:diagnosis, but clinical impressions concerning alcohol problems can
./technical/government/Alcohol_Problems/Session2-PDF.txt:be inaccurate. Trained practitioners counseling alcoholics could
./technical/government/Alcohol_Problems/Session2-PDF.txt:patients with alcohol problems. Unfortunately, the majority of
./technical/government/Alcohol_Problems/Session2-PDF.txt:reported that in a trauma center ED, staff suspected alcohol-ism in
./technical/government/Alcohol_Problems/Session2-PDF.txt:a sensitivity of 29% for alcohol problems in the ED.7
./technical/government/Alcohol_Problems/Session2-PDF.txt:Self-report may be enhanced when specific alcohol questions are
./technical/government/Alcohol_Problems/Session2-PDF.txt:to detect alcohol use disorders. The CAGE was developed in 1968 as
./technical/government/Alcohol_Problems/Session2-PDF.txt:a brief screening tool for primary care providers to detect alcohol
./technical/government/Alcohol_Problems/Session2-PDF.txt:The MAST (Michigan Alcohol-Screening Test), developed in 1971 as
./technical/government/Alcohol_Problems/Session2-PDF.txt:a screen for alcohol abuse and dependence, has 24 yes/no questions.
./technical/government/Alcohol_Problems/Session2-PDF.txt:SAAST (Self-Administered Alcoholism Screening Test) was
./technical/government/Alcohol_Problems/Session2-PDF.txt:developed in 1972 to screen for alcohol abuse and dependence. It
./technical/government/Alcohol_Problems/Session2-PDF.txt:drinkers. WHO developed the AUDIT (Alcohol Use Disorder
./technical/government/Alcohol_Problems/Session2-PDF.txt:at-risk drinking in addition to alcohol abuse and dependence. AUDIT
./technical/government/Alcohol_Problems/Session2-PDF.txt:about even lower levels of alcohol consumption in this group has
./technical/government/Alcohol_Problems/Session2-PDF.txt:screens for alcohol abuse and dependence. It has five questions,
./technical/government/Alcohol_Problems/Session2-PDF.txt:minutes to administer.33 T-ACE also screens for alcohol abuse and
./technical/government/Alcohol_Problems/Session2-PDF.txt:at-risk drinking, alcohol abuse, and dependence. It is a
./technical/government/Alcohol_Problems/Session2-PDF.txt:Rapid Alcohol Assessment Screen (RAPS4). Cherpitel screened an ED
./technical/government/Alcohol_Problems/Session2-PDF.txt:alcohol?"- followed by three questions about alcohol consumption
./technical/government/Alcohol_Problems/Session2-PDF.txt:an ICD-10 diagnosis of alcohol dependence.7 In the second study,
./technical/government/Alcohol_Problems/Session2-PDF.txt:with an ICD-10 or DSM-IV diagnosis of alcohol dependence, harmful
./technical/government/Alcohol_Problems/Session2-PDF.txt:84%, for a DSM-IV diagnosis of alcohol dependence.37 Fiellin
./technical/government/Alcohol_Problems/Session2-PDF.txt:reviewed 38 studies of screening for alcohol use disorder in the
./technical/government/Alcohol_Problems/Session2-PDF.txt:For alcohol abuse or dependence, CAGE was found most effective with
./technical/government/Alcohol_Problems/Session2-PDF.txt:best within the spectrum of alcohol use they were developed to
./technical/government/Alcohol_Problems/Session2-PDF.txt:were the best tests for alcohol dependence among women. Their
./technical/government/Alcohol_Problems/Session2-PDF.txt:sensitivities (59% and 48% respectively) for alcohol dependence
./technical/government/Alcohol_Problems/Session2-PDF.txt:Alcohol concentration
./technical/government/Alcohol_Problems/Session2-PDF.txt:identify intoxication. The presence of alcohol may not always
./technical/government/Alcohol_Problems/Session2-PDF.txt:indicate an alcohol problem. While a very high BAC in an unimpaired
./technical/government/Alcohol_Problems/Session2-PDF.txt:insensitive screen for an alcohol use disorder. One study found
./technical/government/Alcohol_Problems/Session2-PDF.txt:that only one-third of intoxicated drivers had an alcohol use
./technical/government/Alcohol_Problems/Session2-PDF.txt:disorder.43 In an ED study, BAC was a poor screen for alcohol abuse
./technical/government/Alcohol_Problems/Session2-PDF.txt:self-reported drinking.7 In another ED study, a saliva alcohol
./technical/government/Alcohol_Problems/Session2-PDF.txt:center, BAC had a sensitivity of 63% for an alcohol disorder.5
./technical/government/Alcohol_Problems/Session2-PDF.txt:with sensitivities of 13% to 67% for alcohol use disorders or
./technical/government/Alcohol_Problems/Session2-PDF.txt:and confronting patients with their blood alcohol levels may
./technical/government/Alcohol_Problems/Session2-PDF.txt:reveal the negative consequences or link alcohol to current
./technical/government/Alcohol_Problems/Session2-PDF.txt:staff does not use structured questionnaires for alcohol screening.
./technical/government/Alcohol_Problems/Session2-PDF.txt:ED staff has no systematic approach to alcohol screening. Staff
./technical/government/Alcohol_Problems/Session2-PDF.txt:rates. EDs have reported high case rates of alcohol problems,
./technical/government/Alcohol_Problems/Session2-PDF.txt:trauma, injuries, assaults,72 depression, and alcohol-related
./technical/government/Alcohol_Problems/Session2-PDF.txt:ED patient care should be improved by implementing alcohol
./technical/government/Alcohol_Problems/Session2-PDF.txt:the lack of counseling available to address patients' alcohol
./technical/government/Alcohol_Problems/Session2-PDF.txt:Most EDs provide very limited alcohol services. When care is
./technical/government/Alcohol_Problems/Session2-PDF.txt:volume of alcohol-involved patients, and the capacity to undertake
./technical/government/Alcohol_Problems/Session2-PDF.txt:4. National Institute on Alcohol Abuse and Alcoholism. The
./technical/government/Alcohol_Problems/Session2-PDF.txt:Physician's Guide to Helping Patients with Alcohol Problems.
./technical/government/Alcohol_Problems/Session2-PDF.txt:the CAGE, the Brief Michigan Alcoholism Screening Test, and the
./technical/government/Alcohol_Problems/Session2-PDF.txt:Alcohol Use Disorders Identification Test in screening trauma
./technical/government/Alcohol_Problems/Session2-PDF.txt:center patients for alcoholism. J Trauma 1997;43:962-9.
./technical/government/Alcohol_Problems/Session2-PDF.txt:6. Gale T, Ja W, Welty T. Differences in detection of alcohol
./technical/government/Alcohol_Problems/Session2-PDF.txt:7. Cherpitel C. Screening for alcohol problems in the emergency
./technical/government/Alcohol_Problems/Session2-PDF.txt:8. Cherpitel C. Comparison of screening instruments for alcohol
./technical/government/Alcohol_Problems/Session2-PDF.txt:regions of the country. Alcohol Clin Exp Res 1997;21:1391-7.
./technical/government/Alcohol_Problems/Session2-PDF.txt:alcohol intoxication and chronic alcohol abuse on outcome from
./technical/government/Alcohol_Problems/Session2-PDF.txt:alcohol problems in the emergency department, part 1: improving
./technical/government/Alcohol_Problems/Session2-PDF.txt:the breath alcohol analyzer. Ann Emerg Med 1984;13:516-20.
./technical/government/Alcohol_Problems/Session2-PDF.txt:12. Gibb K. Serum alcohol levels, toxicology screens, and use
./technical/government/Alcohol_Problems/Session2-PDF.txt:of the breath alcohol analyzer. Ann Emerg Med 1986;15:349-53.
./technical/government/Alcohol_Problems/Session2-PDF.txt:intoxication in alcoholics. J Consult Clin Psychol
./technical/government/Alcohol_Problems/Session2-PDF.txt:Clifford P. Alcohol use among subcritically injured emergency
./technical/government/Alcohol_Problems/Session2-PDF.txt:alcohol-related problems in general practice. J Stud Alcohol
./technical/government/Alcohol_Problems/Session2-PDF.txt:with the Alcohol Use Disorders Identification Test (AUDIT) in an
./technical/government/Alcohol_Problems/Session2-PDF.txt:acute alcohol intoxication and chronic alcohol dependence by trauma
./technical/government/Alcohol_Problems/Session2-PDF.txt:questions in the detection of alcoholism. JAMA 1988;259:51-4.
./technical/government/Alcohol_Problems/Session2-PDF.txt:19. Fleming M, Barry K. The effectiveness of alcoholism
./technical/government/Alcohol_Problems/Session2-PDF.txt:screening in an ambulatory care setting. J Stud Alcohol
./technical/government/Alcohol_Problems/Session2-PDF.txt:20. Fleming M, Barry K. A three-sample test of a masked alcohol
./technical/government/Alcohol_Problems/Session2-PDF.txt:screening questionnaire. Alcohol 1991;26:81-91.
./technical/government/Alcohol_Problems/Session2-PDF.txt:for alcoholism. J Gen Intern Med 1990;5:361-4.
./technical/government/Alcohol_Problems/Session2-PDF.txt:24. Ewing J. Detecting alcoholism: the CAGE questionnaire.
./technical/government/Alcohol_Problems/Session2-PDF.txt:validation of a new alcohol screening instrument. Am J Psychiatry
./technical/government/Alcohol_Problems/Session2-PDF.txt:version of the Michigan Alcoholism Screening Test. Am J Psychiatry
./technical/government/Alcohol_Problems/Session2-PDF.txt:27. Selzer M. The Michigan Alcoholism Screening Test: the quest
./technical/government/Alcohol_Problems/Session2-PDF.txt:Short Michigan Alcoholism Screening Test (SMAST). J Stud Alcohol
./technical/government/Alcohol_Problems/Session2-PDF.txt:analysis of the Self-Administered Alcoholism Screening Test.
./technical/government/Alcohol_Problems/Session2-PDF.txt:Alcohol Clin Exp Res 1987;11:269-73.
./technical/government/Alcohol_Problems/Session2-PDF.txt:30. Davis L, Jr., Morse R. Self-Administered Alcoholism
./technical/government/Alcohol_Problems/Session2-PDF.txt:computer-administered formats. Alcohol Clin Exp Res
./technical/government/Alcohol_Problems/Session2-PDF.txt:31. Saunders J, Aasland O, Amundsen A, Grant M. Alcohol
./technical/government/Alcohol_Problems/Session2-PDF.txt:With Harmful Alcohol Consumption, I. Addiction 1993;88:349-62.
./technical/government/Alcohol_Problems/Session2-PDF.txt:Development of the Alcohol Use Disorders Identification Test
./technical/government/Alcohol_Problems/Session2-PDF.txt:pregnancy risk-drinking. Alcohol Clin Exp Res 1994;18:1156-61.
./technical/government/Alcohol_Problems/Session2-PDF.txt:drinking in the emergency room: the RAPS4. Rapid Alcohol Problems
./technical/government/Alcohol_Problems/Session2-PDF.txt:Screen. J Stud Alcohol 2000;61:447-9.
./technical/government/Alcohol_Problems/Session2-PDF.txt:in an emergency room population. J Stud Alcohol 1998;59:420-6.
./technical/government/Alcohol_Problems/Session2-PDF.txt:the CAGE, the Brief Michigan Alcohol Screening Test, and the
./technical/government/Alcohol_Problems/Session2-PDF.txt:Alcohol Use Disorders Identification Test in screening trauma
./technical/government/Alcohol_Problems/Session2-PDF.txt:center patients for alcoholism. J Trauma 1997; 43:962-9.
./technical/government/Alcohol_Problems/Session2-PDF.txt:38. Fiellin DA, Reid MC, O'Connor PG. Screening for alcohol
./technical/government/Alcohol_Problems/Session2-PDF.txt:screening instruments for identifying harmful drinking and alcohol
./technical/government/Alcohol_Problems/Session2-PDF.txt:dependence in the emergency room. Alcohol Clin Exp Res
./technical/government/Alcohol_Problems/Session2-PDF.txt:instruments for alcohol problems in the emergency room. J Stud
./technical/government/Alcohol_Problems/Session2-PDF.txt:Alcohol 1995;56:695-700.
./technical/government/Alcohol_Problems/Session2-PDF.txt:41. Bradley KA, Boyd-Wickizer J, Powell SH, Burman ML. Alcohol
./technical/government/Alcohol_Problems/Session2-PDF.txt:Alcoholism. Criteria for the diagnosis of alcoholism. Am J
./technical/government/Alcohol_Problems/Session2-PDF.txt:43. Gijbers A, Raymond A, Whelan G, et al. Does a blood alcohol
./technical/government/Alcohol_Problems/Session2-PDF.txt:M. Prevalence and recognition of alcohol abuse in a primary care
./technical/government/Alcohol_Problems/Session2-PDF.txt:alcoholism in primary health care: compared efficacy of different
./technical/government/Alcohol_Problems/Session2-PDF.txt:instruments. Drug Alcohol Depend 1995;40:151-8.
./technical/government/Alcohol_Problems/Session2-PDF.txt:Objective diagnosis of alcohol abuse: compared values of
./technical/government/Alcohol_Problems/Session2-PDF.txt:transferase (GGT), and mean corpuscular volume (MCV). Alcohol Clin
./technical/government/Alcohol_Problems/Session2-PDF.txt:clinic: is this test useful in assessing alcohol consumption?
./technical/government/Alcohol_Problems/Session2-PDF.txt:Alcohol. 1998;33:304-9.
./technical/government/Alcohol_Problems/Session2-PDF.txt:transferrin and conventional alcohol markers as indicators for
./technical/government/Alcohol_Problems/Session2-PDF.txt:Alcohol Clin Exp Res 1998;22:892-6.
./technical/government/Alcohol_Problems/Session2-PDF.txt:A. Screening for excessive alcohol drinking: comparative value of
./technical/government/Alcohol_Problems/Session2-PDF.txt:criterion-oriented validation of an alcoholism questionnaire in
./technical/government/Alcohol_Problems/Session2-PDF.txt:Cigarette, alcohol, and other drug use by school-age pregnant
./technical/government/Alcohol_Problems/Session2-PDF.txt:brief intervention for adolescent alcohol use. Arch Pediatr Adolesc
./technical/government/Alcohol_Problems/Session2-PDF.txt:and the risk of alcohol dependence. Addiction 1993;88:1209-18.
./technical/government/Alcohol_Problems/Session2-PDF.txt:Alcoholism screening in the elderly. J Am Geriatr Soc
./technical/government/Alcohol_Problems/Session2-PDF.txt:62. Bercsi S, Brickner P, Saha D. Alcohol use and abuse in the
./technical/government/Alcohol_Problems/Session2-PDF.txt:Alcohol Depend 1993;33:139-49.
./technical/government/Alcohol_Problems/Session2-PDF.txt:H. Identification of alcoholism and depression in a geriatric
./technical/government/Alcohol_Problems/Session2-PDF.txt:64. Fink A, Hays RD, Moore AA, Beck JC. Alcohol-related
./technical/government/Alcohol_Problems/Session2-PDF.txt:encountered with opportunistic screening for alcohol-related
./technical/government/Alcohol_Problems/Session2-PDF.txt:68. Burke T. The economic impact of alcohol abuse a
./technical/government/Alcohol_Problems/Session3-PDF.txt:Intervening with Alcohol Problems
./technical/government/Alcohol_Problems/Session3-PDF.txt:Excessive alcohol consumption plays an important role in many of
./technical/government/Alcohol_Problems/Session3-PDF.txt:documented the presence of alcohol among patients admitted to
./technical/government/Alcohol_Problems/Session3-PDF.txt:studies have demonstrated that even blood alcohol concentration
./technical/government/Alcohol_Problems/Session3-PDF.txt:(BAC) determinations under-estimate the extent of alcohol problems
./technical/government/Alcohol_Problems/Session3-PDF.txt:admission, and the fact that alcohol is a risk factor both for the
./technical/government/Alcohol_Problems/Session3-PDF.txt:alcohol problems in these settings.8-12 Although there are problems
./technical/government/Alcohol_Problems/Session3-PDF.txt:intervening effectively with alcohol problems in emergency
./technical/government/Alcohol_Problems/Session3-PDF.txt:patients with alcohol problems encountered in the emergency
./technical/government/Alcohol_Problems/Session3-PDF.txt:asked, "To what extent do you believe your alcohol consumption was
./technical/government/Alcohol_Problems/Session3-PDF.txt:We do know that alcohol consumption changes for many problem
./technical/government/Alcohol_Problems/Session3-PDF.txt:However, changes in alcohol consumption are often not sustained
./technical/government/Alcohol_Problems/Session3-PDF.txt:emergency department seem to dissipate without an alcohol-specific
./technical/government/Alcohol_Problems/Session3-PDF.txt:of re-admission or prevent re-injury related to alcohol
./technical/government/Alcohol_Problems/Session3-PDF.txt:alcohol workers intervening with problem drinkers. A brief
./technical/government/Alcohol_Problems/Session3-PDF.txt:intervention in an emergency department by alcohol health workers
./technical/government/Alcohol_Problems/Session3-PDF.txt:referral to alcoholism treatment for patients and families who
./technical/government/Alcohol_Problems/Session3-PDF.txt:alcohol treatment in 62% of the 100 consecutive cases
./technical/government/Alcohol_Problems/Session3-PDF.txt:drinking or in successful connection with appropriate alcohol
./technical/government/Alcohol_Problems/Session3-PDF.txt:have used blood alcohol concentration as one of the critical
./technical/government/Alcohol_Problems/Session3-PDF.txt:the mechanism of action of these interventions was reduced alcohol
./technical/government/Alcohol_Problems/Session3-PDF.txt:alcohol consumption and consequences. Several current publications
./technical/government/Alcohol_Problems/Session3-PDF.txt:combination of blood alcohol concentration (BAC), serum gamma
./technical/government/Alcohol_Problems/Session3-PDF.txt:reduction occurred among the patients with mild to moderate alcohol
./technical/government/Alcohol_Problems/Session3-PDF.txt:with more chronic and severe alcohol dependence. Another limitation
./technical/government/Alcohol_Problems/Session3-PDF.txt:following an alcohol-related event randomly assigned 94 of the 184
./technical/government/Alcohol_Problems/Session3-PDF.txt:driving and a list of alcohol treatment agencies. The intervention,
./technical/government/Alcohol_Problems/Session3-PDF.txt:alcohol-related injuries, and alcohol-related problems were
./technical/government/Alcohol_Problems/Session3-PDF.txt:specialists trained in alcohol or substance abuse counseling or in
./technical/government/Alcohol_Problems/Session3-PDF.txt:avoid alcohol-related injuries in the future. Substance abuse
./technical/government/Alcohol_Problems/Session3-PDF.txt:settings have delivered brief alcohol-focused interventions. These
./technical/government/Alcohol_Problems/Session3-PDF.txt:brief, patient-centered alcohol counseling intervention delivered
./technical/government/Alcohol_Problems/Session3-PDF.txt:produced significant reductions in alcohol consumption among both
./technical/government/Alcohol_Problems/Session3-PDF.txt:alcohol intervention.9,26,35,36 However, few studies of
./technical/government/Alcohol_Problems/Session3-PDF.txt:these alcohol-focused interventions for a variety of practical,
./technical/government/Alcohol_Problems/Session3-PDF.txt:problematic alcohol consumption, the connection between injury and
./technical/government/Alcohol_Problems/Session3-PDF.txt:alcohol is the goal of these treatment programs.37 On the other
./technical/government/Alcohol_Problems/Session3-PDF.txt:additional treatment or self-help groups like Alcoholics Anonymous.
./technical/government/Alcohol_Problems/Session3-PDF.txt:abstinence from alcohol.
./technical/government/Alcohol_Problems/Session3-PDF.txt:alcohol interventions.25 However, postponing intervention to the
./technical/government/Alcohol_Problems/Session3-PDF.txt:alcohol interventions in medical settings have been effective,32
./technical/government/Alcohol_Problems/Session3-PDF.txt:department and trauma center patients into alcoholism
./technical/government/Alcohol_Problems/Session3-PDF.txt:This review of interventions, focused on addressing alcohol
./technical/government/Alcohol_Problems/Session3-PDF.txt:have alcohol use problems, and there are published guidelines for
./technical/government/Alcohol_Problems/Session3-PDF.txt:positioned to implement pro-grams of alcohol screening,
./technical/government/Alcohol_Problems/Session3-PDF.txt:control and prevention, little has been done to incorporate alcohol
./technical/government/Alcohol_Problems/Session3-PDF.txt:of trauma centers which revealed that blood alcohol testing, which
./technical/government/Alcohol_Problems/Session3-PDF.txt:to identify patients with alcohol use problems.
./technical/government/Alcohol_Problems/Session3-PDF.txt:regarding alcohol problems in emergency departments, a survey of
./technical/government/Alcohol_Problems/Session3-PDF.txt:alcohol-impaired drivers.41 However, ambivalent attitudes were
./technical/government/Alcohol_Problems/Session3-PDF.txt:revealed concerning alcoholics and alcoholism. On a scale of 0
./technical/government/Alcohol_Problems/Session3-PDF.txt:(strongly disagree) to 7 (strongly agree) the statement "alcoholics
./technical/government/Alcohol_Problems/Session3-PDF.txt:statement "alcoholism is a treat-able disease" received a mean
./technical/government/Alcohol_Problems/Session3-PDF.txt:"defeatism about alcoholism management." In a recent survey of
./technical/government/Alcohol_Problems/Session3-PDF.txt:emergency medicine physicians, 78% agreed that alcohol
./technical/government/Alcohol_Problems/Session3-PDF.txt:asking about alcohol use but few used recommended screening
./technical/government/Alcohol_Problems/Session3-PDF.txt:settings to reduce drinking and alcohol related risks. The first
./technical/government/Alcohol_Problems/Session3-PDF.txt:admission and triage system of the emergency settings. Alcohol
./technical/government/Alcohol_Problems/Session3-PDF.txt:problems can be identified along a range of alcohol use and
./technical/government/Alcohol_Problems/Session3-PDF.txt:set for more or less severe alcohol problems. However, whatever the
./technical/government/Alcohol_Problems/Session3-PDF.txt:the alcohol problem and the needs of the patient. Many treatment
./technical/government/Alcohol_Problems/Session3-PDF.txt:by level of alcohol problem, although controlled trials do not
./technical/government/Alcohol_Problems/Session3-PDF.txt:day treatment. Self-help groups like Alcoholics Anonymous, Women
./technical/government/Alcohol_Problems/Session3-PDF.txt:screening instrument that identifies individuals with alcohol
./technical/government/Alcohol_Problems/Session3-PDF.txt:interventions, understand alcohol problems, and are armed with a
./technical/government/Alcohol_Problems/Session3-PDF.txt:levels of severity? Individuals with less severe alcohol problems
./technical/government/Alcohol_Problems/Session3-PDF.txt:the intervention for alcohol problems? Most emergency department
./technical/government/Alcohol_Problems/Session3-PDF.txt:make interventions for alcohol problems more feasible? For example,
./technical/government/Alcohol_Problems/Session3-PDF.txt:template with options incorporating the alcohol problem
./technical/government/Alcohol_Problems/Session3-PDF.txt:been published that deal with alcohol dependence and abuse and
./technical/government/Alcohol_Problems/Session3-PDF.txt:Zuska, a surgeon with an interest in alcohol problems among injured
./technical/government/Alcohol_Problems/Session3-PDF.txt:patients noted: "The crisis that brings the alcoholic to the
./technical/government/Alcohol_Problems/Session3-PDF.txt:alcohol problems have the potential to reduce alcohol-related
./technical/government/Alcohol_Problems/Session3-PDF.txt:1. Cherpitel CJ. Screening for alcohol problems in the
./technical/government/Alcohol_Problems/Session3-PDF.txt:2. Degutis LC. Screening for alcohol problems in emergency
./technical/government/Alcohol_Problems/Session3-PDF.txt:3. Ewing JA. Detecting alcoholism: the CAGE questionnaire. JAMA
./technical/government/Alcohol_Problems/Session3-PDF.txt:4. Maio RF, Waller PF, Blow FC, Hill EM, Singer KM. Alcohol
./technical/government/Alcohol_Problems/Session3-PDF.txt:5. Whiteman PJ, Hoffman RS, Goldfrank LR. Alcoholism in the
./technical/government/Alcohol_Problems/Session3-PDF.txt:alcohol abuse in trauma patients. Arch Surg 1993;128:907-13.
./technical/government/Alcohol_Problems/Session3-PDF.txt:PA, Craig SA, Zink BJ. Patients with alcohol problems in the
./technical/government/Alcohol_Problems/Session3-PDF.txt:PA, Craig SA, Zink BJ. Patients with alcohol problems in the
./technical/government/Alcohol_Problems/Session3-PDF.txt:10. Gentilello LM, Donovan DM, Dunn CW, Rivara FP. Alcohol
./technical/government/Alcohol_Problems/Session3-PDF.txt:11. Lowenstein SR, Weissberg MP, Terry D. Alcohol intoxication,
./technical/government/Alcohol_Problems/Session3-PDF.txt:role of alcohol and other drugs-an EAST position paper prepared by
./technical/government/Alcohol_Problems/Session3-PDF.txt:alcohol-related injuries. Substance abuse interventions in general
./technical/government/Alcohol_Problems/Session3-PDF.txt:Russlee AC. Attribution of injury to alcohol involvement in
./technical/government/Alcohol_Problems/Session3-PDF.txt:seriously injured in alcohol-related motor vehicle crashes.
./technical/government/Alcohol_Problems/Session3-PDF.txt:analysis of injury by cause among casualty. Alcohol Clin Exp
./technical/government/Alcohol_Problems/Session3-PDF.txt:18. Gentilello LM, Rivara FP, Donovan DM, et al. Alcohol
./technical/government/Alcohol_Problems/Session3-PDF.txt:reduction with alcohol-positive older adolescents in a
./technical/government/Alcohol_Problems/Session3-PDF.txt:opportunity to initiate treatment in the alcoholic. Am J Surg
./technical/government/Alcohol_Problems/Session3-PDF.txt:alcohol-related trauma. Br J Oral Maxillofac Surg
./technical/government/Alcohol_Problems/Session3-PDF.txt:alcohol health worker in an accident and emergency
./technical/government/Alcohol_Problems/Session3-PDF.txt:department. Alcohol Alcohol
./technical/government/Alcohol_Problems/Session3-PDF.txt:abuse consultation team in a trauma center. J Stud Alcohol
./technical/government/Alcohol_Problems/Session3-PDF.txt:28. Hemphill C, Bennett BE, Watkins, BL. Alcoholism: the
./technical/government/Alcohol_Problems/Session3-PDF.txt:alcohol problems. Acad Emerg Med 2000; 7:1383-92.
./technical/government/Alcohol_Problems/Session3-PDF.txt:review of randomized controlled trials. Alcohol Alcohol
./technical/government/Alcohol_Problems/Session3-PDF.txt:Brief physician advice for problem alcohol drinkers: a randomized
./technical/government/Alcohol_Problems/Session3-PDF.txt:recovery after alcoholism treatment. JAMA 1992;267(5):663-7.
./technical/government/Alcohol_Problems/Session3-PDF.txt:for performing alcohol interventions in trauma centers. J Trauma
./technical/government/Alcohol_Problems/Session3-PDF.txt:36. Reyna TM, Hollis MW, Hulsebus RC. Alcohol-related trauma:
./technical/government/Alcohol_Problems/Session3-PDF.txt:37. Miller WR. Alcoholism: toward a better disease model.
./technical/government/Alcohol_Problems/Session3-PDF.txt:alcohol problems: a review. Addiction 1993;88:315-36.
./technical/government/Alcohol_Problems/Session3-PDF.txt:Mental Health Services Administration. Alcohol and Other Drug
./technical/government/Alcohol_Problems/Session3-PDF.txt:40. Soderstrom CA, Dailey JT, Kerns TJ. Alcohol and other
./technical/government/Alcohol_Problems/Session3-PDF.txt:alcohol-impaired drivers: results from a national survey of
./technical/government/Alcohol_Problems/Session3-PDF.txt:surveillance of alcohol intoxication after motor vehicular
./technical/government/Alcohol_Problems/Session3-PDF.txt:attitudes concerning intervention for alcohol abuse/dependence in
./technical/government/Alcohol_Problems/Session3-PDF.txt:interventions for alcohol problems: a national survey of primary
./technical/government/Alcohol_Problems/Session3-PDF.txt:for excessive drinkers: the need for caution. Alcohol Alcohol
./technical/government/Alcohol_Problems/Session3-PDF.txt:reduce alcohol intake in primary health care populations: a
./technical/government/Alcohol_Problems/Session3-PDF.txt:alcoholism. In: Gurman AS, Jacobson N, editors. Clinical Handbook
./technical/government/Alcohol_Problems/Session3-PDF.txt:trauma patients for alcohol problems: are insurance companies
./technical/government/Alcohol_Problems/Session3-PDF.txt:emergency department (ED) with alcohol problems. We have just heard
./technical/government/Alcohol_Problems/Session3-PDF.txt:to report heavy drinking, consequences of drinking, alcohol
./technical/government/Alcohol_Problems/Session3-PDF.txt:dependence, or history of treatment for an alcohol problem.2
./technical/government/Alcohol_Problems/Session3-PDF.txt:patients about their alcohol use. The intervention featured, the
./technical/government/Alcohol_Problems/Session3-PDF.txt:often tracked. Why not include patients with alcohol problems in
./technical/government/Alcohol_Problems/Session3-PDF.txt:alcohol consumption or decreases in negative consequences, such as
./technical/government/Alcohol_Problems/Session3-PDF.txt:department: screening and brief intervention for alcohol problems
./technical/government/Alcohol_Problems/Session3-PDF.txt:and lifestyle change. In: Howard G, editor. Issues in Alcohol Use
./technical/government/Alcohol_Problems/Session3-PDF.txt:alcoholic client: The influence of experience, support, training,
./technical/government/Alcohol_Problems/Session3-PDF.txt:psychotherapy for alcohol dependence. Arch Gen Psychiatry
./technical/government/Alcohol_Problems/Session3-PDF.txt:Intervening with Alcohol Problems in
./technical/government/Alcohol_Problems/Session3-PDF.txt:Reducing death and disability related to alcohol remains a
./technical/government/Alcohol_Problems/Session3-PDF.txt:identify alcohol problems and to begin interventions, particularly
./technical/government/Alcohol_Problems/Session3-PDF.txt:compelling reasons make the ED an important setting for alcohol
./technical/government/Alcohol_Problems/Session3-PDF.txt:alcohol problems are released from the ED rather than being
./technical/government/Alcohol_Problems/Session3-PDF.txt:identification of and intervention for an alcohol problem.
./technical/government/Alcohol_Problems/Session3-PDF.txt:efficacy and ultimate effectiveness of brief alcohol interventions
./technical/government/Alcohol_Problems/Session3-PDF.txt:or alcohol-dependent drinkers. It is clear from their manuscript
./technical/government/Alcohol_Problems/Session3-PDF.txt:that a spectrum of alcohol problems presents in the ED and that a
./technical/government/Alcohol_Problems/Session3-PDF.txt:or deliver brief alcohol interventions in the ED. Previous research
./technical/government/Alcohol_Problems/Session3-PDF.txt:attrition rates, types of interventions, levels of alcohol use,
./technical/government/Alcohol_Problems/Session3-PDF.txt:drinkers, problem drinkers, alcohol-dependent drinkers) and the
./technical/government/Alcohol_Problems/Session3-PDF.txt:Brief alcohol interventions have generally included feedback by
./technical/government/Alcohol_Problems/Session3-PDF.txt:positive) to questions about alcohol consumption or consequences.
./technical/government/Alcohol_Problems/Session3-PDF.txt:effective, an ED-based brief alcohol intervention model that
./technical/government/Alcohol_Problems/Session3-PDF.txt:alcohol use. It is thought that this is particularly true if the
./technical/government/Alcohol_Problems/Session3-PDF.txt:providers cannot easily find time to conduct brief alcohol
./technical/government/Alcohol_Problems/Session3-PDF.txt:interest in doing alcohol interventions in the ED. On the other
./technical/government/Alcohol_Problems/Session3-PDF.txt:it difficult to address alcohol issues at all, particularly for
./technical/government/Alcohol_Problems/Session3-PDF.txt:conditions clearly linked to alcohol consumption.
./technical/government/Alcohol_Problems/Session3-PDF.txt:The implementation of brief alcohol intervention systems in
./technical/government/Alcohol_Problems/Session3-PDF.txt:first step, but implementation of proven alcohol screening and
./technical/government/Alcohol_Problems/Session3-PDF.txt:alcohol consumption of at-risk drinkers and the limited time for
./technical/government/Alcohol_Problems/Session3-PDF.txt:research on brief alcohol interventions specifically with the use
./technical/government/Alcohol_Problems/Session3-PDF.txt:positive for at-risk drinking or more serious alcohol-related
./technical/government/Alcohol_Problems/Session3-PDF.txt:system of intervention. Just as there is a spectrum of alcohol use
./technical/government/Alcohol_Problems/Session3-PDF.txt:New directions in brief alcohol interventions in emergency
./technical/government/Alcohol_Problems/Session3-PDF.txt:multiple health risks (e.g., smoking, alcohol use, seat belt use),
./technical/government/Alcohol_Problems/Session3-PDF.txt:to alcohol misuse and abuse.
./technical/government/Alcohol_Problems/Session3-PDF.txt:alcohol problems to those with severe dependence. In the next few
./technical/government/Alcohol_Problems/Session3-PDF.txt:alcohol use. Any methods that are developed with researchers and
./technical/government/Alcohol_Problems/Session3-PDF.txt:of alcohol-related emergency room admission. J Stud Alcohol
./technical/government/Alcohol_Problems/Session3-PDF.txt:4. Cherpitel CJ. Alcohol, Injury, and risk-taking behavior:
./technical/government/Alcohol_Problems/Session3-PDF.txt:data from a national sample. Alcohol Clin Exp Res
./technical/government/Alcohol_Problems/Session3-PDF.txt:5. Dewey KE. Alcohol related attendances at the accident and
./technical/government/Alcohol_Problems/Session3-PDF.txt:6. Zink BJ, Maio RF. Alcohol use and trauma. Acad Emerg Med
./technical/government/Alcohol_Problems/Session3-PDF.txt:7. Maio RF. Alcohol and injury in the emergency department:
./technical/government/Alcohol_Problems/Session3-PDF.txt:alcohol-related injuries. Substance abuse interventions in general
./technical/government/Alcohol_Problems/Session3-PDF.txt:McCarthy M, Russlee AC. Attribution of injury to alcohol
./technical/government/Alcohol_Problems/Session3-PDF.txt:involvement in young adults seriously injured in alcohol-related
./technical/government/Alcohol_Problems/Session3-PDF.txt:of Alcohol-related Problems. Report on Phase II: A Randomized
./technical/government/Alcohol_Problems/Session3-PDF.txt:physician advice for problem alcohol drinkers: a randomized
./technical/government/Alcohol_Problems/Session3-PDF.txt:alcohol health worker in an accident and emergency
./technical/government/Alcohol_Problems/Session3-PDF.txt:department. Alcohol Alcohol
./technical/government/Alcohol_Problems/Session3-PDF.txt:controlled trials. Alcohol Alcohol 1999;34:609-21.
./technical/government/Alcohol_Problems/Session3-PDF.txt:CW, et al. Alcohol interventions in a trauma center as a
./technical/government/Alcohol_Problems/Session3-PDF.txt:what motivates patients to change their use of alcohol. He noted
./technical/government/Alcohol_Problems/Session3-PDF.txt:alcohol or not, patients did equally well at follow-up.
./technical/government/Alcohol_Problems/Session3-PDF.txt:alcohol-related negative consequences and injuries at 1 year.
./technical/government/Alcohol_Problems/Session3-PDF.txt:of the study was to encourage post-discharge alcohol treatment, but
./technical/government/Alcohol_Problems/Session3-PDF.txt:Alcoholics Anonymous session. Consequently, he questioned how
./technical/government/Alcohol_Problems/Session3-PDF.txt:alcohol-related harm, he was disappointed to find no effect on
./technical/government/Alcohol_Problems/Session3-PDF.txt:Many of the college students who visit the ED have mild alcohol
./technical/government/Alcohol_Problems/Session3-PDF.txt:problems and are confident they could overcome their alcohol
./technical/government/Alcohol_Problems/Session3-PDF.txt:control groups receive so much attention focused on alcohol that it
./technical/government/Alcohol_Problems/Session3-PDF.txt:about alcohol, and that could affect their answers. These
./technical/government/Alcohol_Problems/Session3-PDF.txt:severe alcohol problems is premature. In his study of adolescents,
./technical/government/Alcohol_Problems/Session3-PDF.txt:participate in research still had measurable blood alcohol levels.
./technical/government/Alcohol_Problems/Session3-PDF.txt:correlate mental status exam scores with alcohol levels at the time
./technical/government/Alcohol_Problems/Session3-PDF.txt:blood alcohol level patients could remember an intervention. If
./technical/government/Alcohol_Problems/Session3-PDF.txt:they know we need to be addressing alcohol problems. She asked the
./technical/government/Alcohol_Problems/Session3-PDF.txt:alcohol problems.
./technical/government/Alcohol_Problems/Session3-PDF.txt:like an appropriate venue for alcohol interventions because many ED
./technical/government/Alcohol_Problems/Session3-PDF.txt:patients have alcohol problems and the ED visit may represent a
./technical/government/Alcohol_Problems/Session3-PDF.txt:screen for alcohol-related problems, then primary care has failed.
./technical/government/Alcohol_Problems/Session3-PDF.txt:resources currently spent on alcohol problems in the ED. She noted
./technical/government/Alcohol_Problems/Session3-PDF.txt:that we have to help patients who have severe alcohol problems.
./technical/government/Alcohol_Problems/Session3-PDF.txt:severity of injury, degree of alcohol dependence, readiness to
./technical/government/Alcohol_Problems/Session3-PDF.txt:Patricia Perry reported that one alcohol intervention project in
./technical/government/Alcohol_Problems/Session3-PDF.txt:Jean Shope expressed her belief that addressing alcohol problems
./technical/government/Alcohol_Problems/Session3-PDF.txt:believed that the ED setting is just one of many where alcohol
./technical/government/Alcohol_Problems/Session3-PDF.txt:selling alcohol interventions because they are in competition with
./technical/government/Alcohol_Problems/Session3-PDF.txt:alcoholics anymore. Most use other substances as well, so it is
./technical/government/Alcohol_Problems/Session3-PDF.txt:it did not lead to changes in alcohol variables or weapon
./technical/government/Alcohol_Problems/Session3-PDF.txt:of alcohol problems was higher than other risk factors. Physicians
./technical/government/Alcohol_Problems/Session4-PDF.txt:Individuals who may benefit from alcohol counseling are often
./technical/government/Alcohol_Problems/Session4-PDF.txt:unaware of their need for treatment. The provision of alcohol
./technical/government/Alcohol_Problems/Session4-PDF.txt:more intractable stages of alcoholism. Finally, such interventions
./technical/government/Alcohol_Problems/Session4-PDF.txt:As proven alcohol interventions emerge, a systematic effort is
./technical/government/Alcohol_Problems/Session4-PDF.txt:that have limited the provision of alcohol intervention and
./technical/government/Alcohol_Problems/Session4-PDF.txt:alcohol problems, and more than 75% were not familiar with any of
./technical/government/Alcohol_Problems/Session4-PDF.txt:the commonly used alcohol screening questionnaires, such as the
./technical/government/Alcohol_Problems/Session4-PDF.txt:quantity/ frequency of alcohol use questions needed to establish an
./technical/government/Alcohol_Problems/Session4-PDF.txt:early diagnosis of an alcohol-related disorder.21 A more recent
./technical/government/Alcohol_Problems/Session4-PDF.txt:screening blood alcohol level can be obtained easily when blood is
./technical/government/Alcohol_Problems/Session4-PDF.txt:not share this concern. Trials of alcohol screening in primary
./technical/government/Alcohol_Problems/Session4-PDF.txt:Some physicians are willing to detect alcohol use, but they
./technical/government/Alcohol_Problems/Session4-PDF.txt:generally fail to diagnose alcohol problems unless a formal
./technical/government/Alcohol_Problems/Session4-PDF.txt:2,002 patients for alcohol problems, but the results were not
./technical/government/Alcohol_Problems/Session4-PDF.txt:g/dl) or had a chronic alcohol problem. Although 45% of patients
./technical/government/Alcohol_Problems/Session4-PDF.txt:had no alcohol in their blood. Patient's age, income, and insurance
./technical/government/Alcohol_Problems/Session4-PDF.txt:make screening worthwhile." An assessment of blood alcohol testing
./technical/government/Alcohol_Problems/Session4-PDF.txt:alcohol concentration believe the test is "not clinically
./technical/government/Alcohol_Problems/Session4-PDF.txt:important" because knowledge of the patient's blood alcohol level
./technical/government/Alcohol_Problems/Session4-PDF.txt:address alcohol problems.29 Their perception of treatment efficacy
./technical/government/Alcohol_Problems/Session4-PDF.txt:alcohol treatment that has led to expert consensus recommendations
./technical/government/Alcohol_Problems/Session4-PDF.txt:that all patients at risk for alcohol problems should be screened
./technical/government/Alcohol_Problems/Session4-PDF.txt:that alcohol problems are outside their practice
./technical/government/Alcohol_Problems/Session4-PDF.txt:integrating alcohol treatment services into emergency care assume
./technical/government/Alcohol_Problems/Session4-PDF.txt:who endorse the concept that alcohol screening and intervention is
./technical/government/Alcohol_Problems/Session4-PDF.txt:their responsibility. Funding for alcohol-related research needs to
./technical/government/Alcohol_Problems/Session4-PDF.txt:clinicians, who will endorse and advance the concept of alcohol
./technical/government/Alcohol_Problems/Session4-PDF.txt:"alcoholism AND treatment AND intervention" yielded 47 publications
./technical/government/Alcohol_Problems/Session4-PDF.txt:alcohol interventions in emergency departments were published in
./technical/government/Alcohol_Problems/Session4-PDF.txt:concept that addressing alcohol problems is their responsibility.
./technical/government/Alcohol_Problems/Session4-PDF.txt:because peer-reviewers do not view alcohol-related research as
./technical/government/Alcohol_Problems/Session4-PDF.txt:to obtain funding from alcohol study sections. Reviewers may not be
./technical/government/Alcohol_Problems/Session4-PDF.txt:processes preferred by alcohol research study sections are usually
./technical/government/Alcohol_Problems/Session4-PDF.txt:alcohol research specialists. On the other hand, studies conducted
./technical/government/Alcohol_Problems/Session4-PDF.txt:by alcohol research specialists may not provide clinically relevant
./technical/government/Alcohol_Problems/Session4-PDF.txt:The design and peer-review of studies on alcohol interventions
./technical/government/Alcohol_Problems/Session4-PDF.txt:methodologic design that study sections composed of alcohol
./technical/government/Alcohol_Problems/Session4-PDF.txt:Treatment" theme of the National Treatment Plan.36 Alcohol problems
./technical/government/Alcohol_Problems/Session4-PDF.txt:of health care dollars. Studies on alcohol interventions in
./technical/government/Alcohol_Problems/Session4-PDF.txt:A 1995 meta-analysis of 32 alcohol treatment modalities found
./technical/government/Alcohol_Problems/Session4-PDF.txt:alcohol problems experience an average of 1.32 injury-related
./technical/government/Alcohol_Problems/Session4-PDF.txt:The opposite may be the case. Alcohol-related medical problems,
./technical/government/Alcohol_Problems/Session4-PDF.txt:especially injuries, occur in the entire population of alcohol
./technical/government/Alcohol_Problems/Session4-PDF.txt:care because many alcohol-related events are not related to total
./technical/government/Alcohol_Problems/Session4-PDF.txt:alcohol consumption, but rather to the activities the patient
./technical/government/Alcohol_Problems/Session4-PDF.txt:engages in while drinking and to where, when, and with whom alcohol
./technical/government/Alcohol_Problems/Session4-PDF.txt:disproportionate share of alcohol-related medical consequences, but
./technical/government/Alcohol_Problems/Session4-PDF.txt:alcohol-related problems.39
./technical/government/Alcohol_Problems/Session4-PDF.txt:Alcohol-related problems occur at lower rates, but in much
./technical/government/Alcohol_Problems/Session4-PDF.txt:greater numbers, among patients with mild to moderate alcohol
./technical/government/Alcohol_Problems/Session4-PDF.txt:alcohol-related problems would still present to the emergency
./technical/government/Alcohol_Problems/Session4-PDF.txt:alcoholism, but it constitutes an important issue in its own right
./technical/government/Alcohol_Problems/Session4-PDF.txt:individuals who do not meet diagnostic criteria for alcohol abuse
./technical/government/Alcohol_Problems/Session4-PDF.txt:demonstrate significant effects on subsequent alcohol intake and
./technical/government/Alcohol_Problems/Session4-PDF.txt:Alcohol use among emergency department patients is not likely a
./technical/government/Alcohol_Problems/Session4-PDF.txt:Despite the prevalence of alcohol use disorders, hospital
./technical/government/Alcohol_Problems/Session4-PDF.txt:addressing alcohol problems as part of their mission. Social
./technical/government/Alcohol_Problems/Session4-PDF.txt:important because many people do not report alcohol-related events
./technical/government/Alcohol_Problems/Session4-PDF.txt:Physicians have voiced a common concern about alcohol screening:
./technical/government/Alcohol_Problems/Session4-PDF.txt:to patients if they have a positive blood alcohol or drug screen.
./technical/government/Alcohol_Problems/Session4-PDF.txt:physicians from screening for alcohol problems.52
./technical/government/Alcohol_Problems/Session4-PDF.txt:the UPPL adversely affects their ability to implement alcohol
./technical/government/Alcohol_Problems/Session4-PDF.txt:alcohol use in the medical record has the potential to abridge
./technical/government/Alcohol_Problems/Session4-PDF.txt:Regulations (42 C.F.R. Part 2), Confidentiality of Alcohol and Drug
./technical/government/Alcohol_Problems/Session4-PDF.txt:personnel whose primary function is the provision of alcohol and
./technical/government/Alcohol_Problems/Session4-PDF.txt:alcohol level is obtained to facilitate treatment of an illness or
./technical/government/Alcohol_Problems/Session4-PDF.txt:knowledge, skills, and confidence in alcohol screening and
./technical/government/Alcohol_Problems/Session4-PDF.txt:patterns, studies on alcohol interventions should be framed,
./technical/government/Alcohol_Problems/Session4-PDF.txt:2. Given the magnitude of alcohol problems and the ability of
./technical/government/Alcohol_Problems/Session4-PDF.txt:research on alcohol problems in EDs.
./technical/government/Alcohol_Problems/Session4-PDF.txt:to address alcohol problems is an integral component of the
./technical/government/Alcohol_Problems/Session4-PDF.txt:professional organizations, and alcohol advocacy groups should
./technical/government/Alcohol_Problems/Session4-PDF.txt:hospitals and physicians who screen for alcohol.
./technical/government/Alcohol_Problems/Session4-PDF.txt:treatment. Am J Drug Alcohol Abuse 1996;22:233-46.
./technical/government/Alcohol_Problems/Session4-PDF.txt:for harm reduction with alcohol-positive older adolescents in a
./technical/government/Alcohol_Problems/Session4-PDF.txt:3. Gentilello LM, Rivara FP, Donovan, DM, et al. Alcohol
./technical/government/Alcohol_Problems/Session4-PDF.txt:alcohol problems: a review. Addiction 1993;88:315-35.
./technical/government/Alcohol_Problems/Session4-PDF.txt:alcohol drinkers. J Gen Intern Med 1997;12:274-83.
./technical/government/Alcohol_Problems/Session4-PDF.txt:hospitalized patients. Am J Drug Alcohol Abuse 1997;23:1-13.
./technical/government/Alcohol_Problems/Session4-PDF.txt:trauma surgeons fail to screen for alcohol problems. Arch Surg
./technical/government/Alcohol_Problems/Session4-PDF.txt:transition from research into practice. J Stud Alcohol 1994 (12
./technical/government/Alcohol_Problems/Session4-PDF.txt:Alcohol Health Res World 1989;15:219-20.
./technical/government/Alcohol_Problems/Session4-PDF.txt:regarding the diagnosis and treatment of alcoholism. JAMA
./technical/government/Alcohol_Problems/Session4-PDF.txt:and treatment of alcoholism in hospitalized patients. JAMA
./technical/government/Alcohol_Problems/Session4-PDF.txt:with opportunistic screening for alcohol-related problems in
./technical/government/Alcohol_Problems/Session4-PDF.txt:18. D'Onofrio G. Screening and brief intervention for alcohol
./technical/government/Alcohol_Problems/Session4-PDF.txt:19. Ewing JA. Detecting alcoholism: the CAGE questionnaire.
./technical/government/Alcohol_Problems/Session4-PDF.txt:20. Selzer ML. The Michigan Alcoholism Screening Test: the
./technical/government/Alcohol_Problems/Session4-PDF.txt:21. Krishel S, Richards CF. Alcohol and substance abuse
./technical/government/Alcohol_Problems/Session4-PDF.txt:Stud Alcohol 2000;61:912-5.
./technical/government/Alcohol_Problems/Session4-PDF.txt:the Alcohol Use Disorders Identification Test (AUDIT). Addiction
./technical/government/Alcohol_Problems/Session4-PDF.txt:24. National Institute on Alcohol Abuse and Alcoholism. The
./technical/government/Alcohol_Problems/Session4-PDF.txt:Physician's Guide to Helping Patients with Alcohol Problems.
./technical/government/Alcohol_Problems/Session4-PDF.txt:acute alcohol intoxication and chronic alcohol dependence by trauma
./technical/government/Alcohol_Problems/Session4-PDF.txt:28. Soderstrom CA, Dailey JT, Kerns TJ. Alcohol and other
./technical/government/Alcohol_Problems/Session4-PDF.txt:alcohol-impaired drivers: results from a national survey of
./technical/government/Alcohol_Problems/Session4-PDF.txt:30. Babor TF, Higgens-Biddle JC. Alcohol screening and brief
./technical/government/Alcohol_Problems/Session4-PDF.txt:Alcohol Problems. Washington (DC): National Academy Press;
./technical/government/Alcohol_Problems/Session4-PDF.txt:drinkers in the emergency department. J Stud Alcohol
./technical/government/Alcohol_Problems/Session4-PDF.txt:37. Hester RK, Miller WR. Handbook of Alcoholism Treatment
./technical/government/Alcohol_Problems/Session4-PDF.txt:39. Gerstein DR, editor. Toward the Prevention of Alcohol
./technical/government/Alcohol_Problems/Session4-PDF.txt:hospitalized patients. Am J Drug Alcohol Abuse 1997;23:1-13.
./technical/government/Alcohol_Problems/Session4-PDF.txt:in treatment for alcohol problems: a comparison of three strategies
./technical/government/Alcohol_Problems/Session4-PDF.txt:PA, Craig SA, Zink BJ. Patients with alcohol problems in the
./technical/government/Alcohol_Problems/Session4-PDF.txt:with opportunistic screening for alcohol-related problems in
./technical/government/Alcohol_Problems/Session4-PDF.txt:49. Gentilello LM, Donovan DM, Dunn CW, and Rivara FP. Alcohol
./technical/government/Alcohol_Problems/Session4-PDF.txt:51. New York State Office of Alcoholism and Substance Abuse
./technical/government/Alcohol_Problems/Session4-PDF.txt:trauma patients for alcohol problems: are insurance companies
./technical/government/Alcohol_Problems/Session4-PDF.txt:53. Rostenberg PO, editor. Alcohol and Other Drug Screening of
./technical/government/Alcohol_Problems/Session4-PDF.txt:54. Confidentiality of Alcohol and Drug Abuse Patient Records,
./technical/government/Alcohol_Problems/Session4-PDF.txt:56. National Institute on Alcohol Abuse and Alcoholism. Twelve
./technical/government/Alcohol_Problems/Session4-PDF.txt:therapists treating individuals with alcohol abuse and dependence.
./technical/government/Alcohol_Problems/Session4-PDF.txt:on Alcohol Abuse and Alcoholism; 1995. NIH Publication No.
./technical/government/Alcohol_Problems/Session4-PDF.txt:thoughtful research agenda for addressing alcohol-related problems
./technical/government/Alcohol_Problems/Session4-PDF.txt:and interventions for alcohol-related problems must be integrated
./technical/government/Alcohol_Problems/Session4-PDF.txt:to practice should reflect the spectrum of alcohol use and related
./technical/government/Alcohol_Problems/Session4-PDF.txt:have alcohol-related problems. A series of carefully structured,
./technical/government/Alcohol_Problems/Session4-PDF.txt:users, alcohol abusers, and alcoholics. When I first began
./technical/government/Alcohol_Problems/Session4-PDF.txt:screening; and 3) match the alcohol-related problem to the
./technical/government/Alcohol_Problems/Session4-PDF.txt:population with alcohol problems.
./technical/government/Alcohol_Problems/Session4-PDF.txt:alcohol-related problems.
./technical/government/Alcohol_Problems/Session4-PDF.txt:policies toward alcohol-related problems. Many trauma surgeons and
./technical/government/Alcohol_Problems/Session4-PDF.txt:emergency physicians oppose alcohol screening in the current
./technical/government/Alcohol_Problems/Session4-PDF.txt:nature of alcohol-related problems in the ED. An epidemiologic
./technical/government/Alcohol_Problems/Session4-PDF.txt:agent/vehicle of morbidity and mortality, alcohol, and the
./technical/government/Alcohol_Problems/Session4-PDF.txt:environment in which these groups interface with alcohol.
./technical/government/Alcohol_Problems/Session4-PDF.txt:distribution, and sale of alcohol to high-risk groups and
./technical/government/Alcohol_Problems/Session4-PDF.txt:routinely asked such as, "Where did you buy the alcohol?" and
./technical/government/Alcohol_Problems/Session4-PDF.txt:abuse/individual behavior questions to when and where the alcohol
./technical/government/Alcohol_Problems/Session4-PDF.txt:Research on changing social norms for alcohol use and abuse is
./technical/government/Alcohol_Problems/Session4-PDF.txt:needed for practitioners and patients, given that alcohol-related
./technical/government/Alcohol_Problems/Session4-PDF.txt:own social norms of at risk alcohol usage that will influence their
./technical/government/Alcohol_Problems/Session4-PDF.txt:our shared goal of fewer alcohol-related deaths and injuries.
./technical/government/Alcohol_Problems/Session4-PDF.txt:screening and intervention for and treatment of alcohol problems
./technical/government/Alcohol_Problems/Session4-PDF.txt:intervention, and referral for patients who have alcohol-related
./technical/government/Alcohol_Problems/Session4-PDF.txt:review using the term "alcoholism." While this term may refer to
./technical/government/Alcohol_Problems/Session4-PDF.txt:the patients who are dependent on alcohol, it does not necessarily
./technical/government/Alcohol_Problems/Session4-PDF.txt:the term "alcohol" and searching the indexes of two of the primary
./technical/government/Alcohol_Problems/Session4-PDF.txt:had "alcohol" in the title or were clearly examining
./technical/government/Alcohol_Problems/Session4-PDF.txt:alcohol-related problems. There was also a trend toward an
./technical/government/Alcohol_Problems/Session4-PDF.txt:Several other articles published in 2000 discussed alcohol as a
./technical/government/Alcohol_Problems/Session4-PDF.txt:recommendations for screening and intervention for alcohol problems
./technical/government/Alcohol_Problems/Session4-PDF.txt:boards are not accepting articles about alcohol problems. Perhaps
./technical/government/Alcohol_Problems/Session4-PDF.txt:build upon the strengths of alcohol research methodologists,
./technical/government/Alcohol_Problems/Session4-PDF.txt:that practitioners would not fear that screening for alcohol
./technical/government/Alcohol_Problems/Session4-PDF.txt:coverage for alcohol and other drug problems, and how does this
./technical/government/Alcohol_Problems/Session4-PDF.txt:respect to records of alcohol screening and intervention in the ED,
./technical/government/Alcohol_Problems/Session4-PDF.txt:who have manifested problems with alcohol, we should use
./technical/government/Alcohol_Problems/Session4-PDF.txt:to define the continuum of alcohol problems that we see. We also
./technical/government/Alcohol_Problems/Session4-PDF.txt:alcohol problems are still viewed as sensitive issues, and some
./technical/government/Alcohol_Problems/Session4-PDF.txt:legislation is to implement universal screening for alcohol and
./technical/government/Alcohol_Problems/Session4-PDF.txt:including training about alcohol and other drug problems in the
./technical/government/Alcohol_Problems/Session4-PDF.txt:treatment for alcohol and other drug (AOD) problems to the same
./technical/government/Alcohol_Problems/Session4-PDF.txt:Connecticut, require that anyone who is incapacitated by alcohol be
./technical/government/Alcohol_Problems/Session4-PDF.txt:alcohol. Currently, emergency departments in Connecticut see many
./technical/government/Alcohol_Problems/Session4-PDF.txt:patients with acute alcohol intoxication on a daily basis, but
./technical/government/Alcohol_Problems/Session4-PDF.txt:intervention-an Advanced Alcohol Problem Identification and
./technical/government/Alcohol_Problems/Session4-PDF.txt:Despite the evidence of the relationship between alcohol and
./technical/government/Alcohol_Problems/Session4-PDF.txt:trauma centers be able to perform blood alcohol testing was
./technical/government/Alcohol_Problems/Session4-PDF.txt:ways: a) there is not a sufficient relationship between alcohol and
./technical/government/Alcohol_Problems/Session4-PDF.txt:injury to justify testing for alcohol use in injured patients;
./technical/government/Alcohol_Problems/Session4-PDF.txt:b) issues of alcohol use among injured patients are not in the
./technical/government/Alcohol_Problems/Session4-PDF.txt:issue of alcohol problems among injured patients so testing does
./technical/government/Alcohol_Problems/Session4-PDF.txt:Dr. Gentilello recommends the development of an ED alcohol
./technical/government/Alcohol_Problems/Session4-PDF.txt:there is an ED alcohol research center, will there also be a
./technical/government/Alcohol_Problems/Session4-PDF.txt:primary care alcohol research center, a trauma alcohol research
./technical/government/Alcohol_Problems/Session4-PDF.txt:center, and a critical care alcohol research center? His proposal,
./technical/government/Alcohol_Problems/Session4-PDF.txt:researchers and practitioners, alcohol researchers, community-based
./technical/government/Alcohol_Problems/Session4-PDF.txt:growing the field of alcohol research in emergency medicine. The
./technical/government/Alcohol_Problems/Session4-PDF.txt:In summary, alcohol problems are a significant issue for
./technical/government/Alcohol_Problems/Session4-PDF.txt:PA, Craig SA, Zink BJ. Patients with alcohol problems in the
./technical/government/Alcohol_Problems/Session4-PDF.txt:PA, Craig SA, Zink BJ. Patients with alcohol problems in the
./technical/government/Alcohol_Problems/Session4-PDF.txt:could provide cost data and blood alcohol tests and admission rates
./technical/government/Alcohol_Problems/Session4-PDF.txt:Carl Soderstrom agreed with Gentilello that alcohol-related
./technical/government/Alcohol_Problems/Session4-PDF.txt:requirement to test patients' blood alcohol content for the first
./technical/government/Alcohol_Problems/Session4-PDF.txt:alcohol test in patients with head injuries can be trouble-some.
./technical/government/Alcohol_Problems/Session4-PDF.txt:non-payment for services provided to alcohol-impaired patients, he
./technical/government/Alcohol_Problems/Session4-PDF.txt:legal right to deny payment due to alcohol use.
./technical/government/Alcohol_Problems/Session4-PDF.txt:Stephen Hargarten said that screening for alcohol applies not
./technical/government/Alcohol_Problems/Session4-PDF.txt:alcohol impairment or from alcohol withdrawal during the acute
./technical/government/Alcohol_Problems/Session4-PDF.txt:are responsible for dealing with the results of alcohol screens and
./technical/government/Alcohol_Problems/Session4-PDF.txt:emergency medicine specialists, not just alcohol researchers, to
./technical/government/Alcohol_Problems/Session4-PDF.txt:screening for alcohol problems in EDs is on the horizon. In order
./technical/government/Alcohol_Problems/Session4-PDF.txt:process, but that panels reviewing alcohol interventions in EDs
./technical/government/Alcohol_Problems/Session4-PDF.txt:an ED for many years. Since alcohol interventions in the ED cut
./technical/government/Alcohol_Problems/Session4-PDF.txt:surgeons become interested in alcohol interventions and write
./technical/government/Alcohol_Problems/Session4-PDF.txt:Alcohol Screening Day, an NIAAA-sponsored event, is an opportunity
./technical/government/Alcohol_Problems/Session4-PDF.txt:alcohol-related assessment, which can act as an intervention. He
./technical/government/Alcohol_Problems/Session4-PDF.txt:also agreed with Gentilello that decreased alcohol intake might not
./technical/government/Alcohol_Problems/Session4-PDF.txt:alcohol intake, perhaps studies should focus on re-injury or health
./technical/government/Alcohol_Problems/Session4-PDF.txt:have to do less alcohol intake assessment, and that would mean less
./technical/government/Alcohol_Problems/Session4-PDF.txt:articles from non-MDs. If non-MD, alcohol methodologists could
./technical/government/Alcohol_Problems/Session4-PDF.txt:values. He related that his alcohol studies used to be returned
./technical/government/Alcohol_Problems/Session4-PDF.txt:no longer require him to strike any references that show alcohol
./technical/government/Alcohol_Problems/Session4-PDF.txt:trauma centers and EDs can help alcohol researchers learn more`

  In this example, the `grep` command is searching for the string "Alcohol" in all the files under the     
  directory `/Alcohol_Problems`. It's using the `-i` option, which is 
  case insensitive search, so the `grep` command is matching the string "Alcohol" in all the
  files, while ignoring the cases of the characters. In other words, "Alcohol" and "alcohol"
  are represented the same way. This command-line option is useful because it searches for a specific string 
  that you are looking for in a file or files where the cases of those characters, whether it's upper or 
  lowercase, don't have to match.  


## -r: Recursive Search 

I found this option from the terminal using the `man` command.

Example 1: 

```grep -r "Alzheimer" ./technical/biomed/```

`./technical/biomed//1471-2415-3-5.txt:          Parkinson's disease [ 53 ] and Alzheimer's disease [ 54 ]
./technical/biomed//1471-2210-1-10.txt:        might be beneficial in the treatment of Alzheimer's disease
./technical/biomed//1471-2202-4-16.txt:        diseases, including Parkinson's, Alzheimer's and prion
./technical/biomed//1471-2202-4-16.txt:        other neurodegenerative conditions, including Alzheimer's
./technical/biomed//1471-2377-2-6.txt:        Patients with Alzheimer's disease experience a
./technical/biomed//1471-2377-2-6.txt:        cognitive part of the Alzheimer's Disease Assessment Scale
./technical/biomed//1471-2377-2-6.txt:          mild-to-moderate Alzheimer's disease studied in two
./technical/biomed//1471-2377-2-6.txt:          these trials were diagnosed with Alzheimer's disease
./technical/biomed//1471-2377-2-6.txt:          dependency of patients with Alzheimer's disease [ 9 ] .
./technical/biomed//1471-2377-2-6.txt:          typically observed in patients with Alzheimer's disease.
./technical/biomed//1471-2377-2-6.txt:          disability of patients with Alzheimer's disease.
./technical/biomed//1471-2377-2-6.txt:        daily activities is an important aspect of Alzheimer's for
./technical/biomed//1471-2377-2-6.txt:        Alzheimer's disease [ 18 ] and antipsychotic medications
./technical/biomed//1471-2377-2-6.txt:        in patients with Alzheimer's disease [ 9 10 ] . The
./technical/biomed//1471-2377-2-6.txt:        conducted to study treatments for Alzheimer's disease have
./technical/biomed//1471-2377-2-6.txt:        diagnosed with Alzheimer's disease. Moreover, this
./technical/biomed//1471-2164-3-29.txt:        in early-onset familial Alzheimer's disease. There is
./technical/biomed//1471-2202-2-16.txt:        cholinergic cells. Alzheimer's disease (AD) is
./technical/biomed//1471-2350-3-1.txt:        ] , Alzheimer disease [ 43 44 45 ] , type 1 diabetes [ 46 ]
./technical/biomed//1471-2202-2-14.txt:        visual spatial attention [ 19 ] . Patients with Alzheimer's
./technical/biomed//1471-2202-2-14.txt:        at risk for Alzheimer's disease have been shown to have a
./technical/biomed//1471-2202-2-14.txt:        same direction as the Alzheimer's patients [ 28 ] . Other
./technical/biomed//1471-2202-2-14.txt:        influence orienting in a task similar to ours. Alzheimer's
./technical/biomed//1475-2832-1-1.txt:        Alzheimer's Disease Research Clinical Center, by the
./technical/biomed//1477-7827-1-46.txt:        Alzheimer's disease.
./technical/biomed//1477-7827-1-46.txt:          Neurodegenerative diseases, including Alzheimer's
./technical/biomed//1477-7827-1-46.txt:          is the most obvious consequence of Alzheimer's disease [
./technical/biomed//1477-7827-1-46.txt:        such as Alzheimer's disease, cerebral ischemia, prion
./technical/biomed//1477-7827-1-46.txt:        the prevention and treatment of Alzheimer's disease [ 72 73
./technical/biomed//1477-7827-1-46.txt:        contribute to the development of Alzheimer's disease and
./technical/biomed//1477-7827-1-46.txt:        Alzheimer's disease.
./technical/biomed//1471-2202-2-20.txt:        neurological disorders such as, Alzheimer's disease [ 4 5 ]
./technical/biomed//1471-2202-2-20.txt:        pathophysiologic events in Alzheimer's disease: deposition
./technical/biomed//1471-2202-2-20.txt:        pathophysiologic event(s) in Alzheimer's disease [ 53 54 55
./technical/biomed//1471-2202-2-20.txt:        inflammatory factor prevalent in Alzheimer's disease)
./technical/biomed//1471-2172-2-10.txt:        on Alzheimer's disease as well since cytokines may
./technical/biomed//gb-2003-4-2-r8.txt:        Alzheimer's disease (FAD) [ 48]. 
./technical/biomed//1471-2202-4-3.txt:          (e.g., Parkinson or Alzheimer disease); since, for
./technical/biomed//1472-6947-1-5.txt:            patients with Alzheimer's Disease found improved
./technical/biomed//1472-6947-1-5.txt:        Alzheimer's Disease. The most studied area in home-based
./technical/biomed//1471-2350-2-8.txt:        Alzheimer's disease [ 5, 6, 7].
./technical/biomed//gb-2002-3-10-research0055.txt:          Alzheimer's disease) through the analysis of their`

  In this example, the `grep` command is searching for the string pattern "Alzheimer" in all the files under 
  the directory `/biomed`. It's using the `-r` option, which recursively searches the specified pattern across 
  multiple files or directories/subdirectories. As shown in the output above, in this case, it displays the 
  relative path to each file under the `/biomed` directory, followed by a colon, and the line in the file where 
  it shows that pattern. This command-line option is useful because it tracks down all instances of the 
  specified pattern across multiple directories/subdirectories or files and displays the lines in each file 
  that contain that pattern. This helps a lot if you are doing research on a topic and want to look up a 
  certain word. 

Example 2:

```grep -r "World War II" ./technical/```

`./technical//government/Gen_Account_Office/Testimony_cg00010t.txt:With the U.S. entry into World War II, GAO faced enormous
./technical//government/Gen_Account_Office/d03232sp.txt:Since World War II, the Congress has clarified and expanded that
./technical//government/Gen_Account_Office/d01591sp.txt:20Since World War II, annual growth in GDP per capita has
./technical//government/Gen_Account_Office/d01591sp.txt:every 35 years. Since World War II, annual growth in GDP per capita
./technical//government/Media/It_Pays_to_Know.txt:Lee Kemp, a hearing-impaired World War II disabled vet, also was
./technical//plos/journal.pbio.0020101.txt:        coincidentally after World War II, was Konrad Lorenz (1966). Lorenz's thesis was greeted
./technical//plos/journal.pbio.0020067.txt:        defense—the cavity magnetron that may have turned the course of World War II.
./technical//plos/journal.pbio.0020067.txt:        Bernal, and Dorothy Hodgkin. The other was the pre-World War II work of William Astbury in
./technical//biomed/bcr583.txt:        Norwegian women who were adolescents during World War II,
./technical//911report/chapter-13.5.txt:                World War II (Oxford Univ. Press, 1988), p. 215.
./technical//911report/chapter-13.1.txt:            The men and women of the World War II generation rose to the challenges of the 1940s
./technical//911report/chapter-3.txt:            The FBI's domestic intelligence gathering dates from the 1930s. With World War II
./technical//911report/chapter-3.txt:                in World War II after having first thought the FBI might take that role. The father
./technical//911report/chapter-3.txt:            At the end of World War II, to Donovan's disappointment, President Harry Truman
./technical//911report/chapter-3.txt:                following World War II. The Congressional Reorganization Act of 1946 created the
./technical//911report/chapter-2.txt:                progress. After gaining independence from Western powers following World War II, the`


  In this example, the `grep` command is searching for the string pattern "World War II" in all the directories 
  and subdirectories under the directory `/technical`. It's using the `-r` option, which recursively searches 
  the specified pattern across multiple files or directories/subdirectories. As shown in the output above, in 
  this case, it displays the relative path to each file under each directory and subdirectory, followed by a 
  colon, and the line in the file where it shows that pattern. This command-line option is useful because it 
  tracks down all instances of the specified pattern across multiple directories/subdirectories or files and 
  displays the lines in each file that contain that pattern. This helps a lot if you are doing research on a 
  topic and want to look up a certain word. 


## -c: Count Pattern Occurrences

[freeCodeCamp](https://www.freecodecamp.org/news/grep-command-in-linux-usage-options-and-syntax-examples)

Example 1:

```grep -c "environment" ./technical/government/Env_Prot_Agen/*```

`./technical/government/Env_Prot_Agen/1-3_meth_901.txt:1
./technical/government/Env_Prot_Agen/atx1-6.txt:2
./technical/government/Env_Prot_Agen/bill.txt:16
./technical/government/Env_Prot_Agen/ctf1-6.txt:2
./technical/government/Env_Prot_Agen/ctf7-10.txt:0
./technical/government/Env_Prot_Agen/ctm4-10.txt:1
./technical/government/Env_Prot_Agen/final.txt:26
./technical/government/Env_Prot_Agen/jeffordslieberm.txt:4
./technical/government/Env_Prot_Agen/multi102902.txt:12
./technical/government/Env_Prot_Agen/nov1.txt:30
./technical/government/Env_Prot_Agen/ro_clear_skies_book.txt:11
./technical/government/Env_Prot_Agen/section-by-section_summary.txt:1
./technical/government/Env_Prot_Agen/tech_adden.txt:29
./technical/government/Env_Prot_Agen/tech_sectiong.txt:4`


  In this example, the `grep` command is searching for the string pattern "environment" in all the files under 
  the subdirectory `/Env_Prot_Agen`. It's using the `-c` option, which counts the number of occurrences of 
  the specified string pattern in a file or files. As shown in the output above, in this case, it displays
  the relative path to each file, followed by a colon, and the number of occurrences of that pattern in each 
  file. This command-line option is useful because it tells you how many times a specific string occurs in a 
  file or files. It's especially helpful if you want to know how many times an error message appeared in a log 
  file. 


Example 2:

```grep -c "gene" ./technical/biomed/gb-2003-4-9-r58.txt```

``88``

  In this example, the `grep` command is searching for the string pattern "gene" in the *gb-2003-4-9-r58.txt* 
  file under the directory `/biomed`. It's using the `-c` option, which counts the number of 
  occurrences of the specified string pattern in a file or files. As shown in the output above, in this case, 
  it displays the number of occurrences of that pattern in this file. This command-line option is useful 
  because it tells you how many times a specific string occurs in a file or files. It's especially helpful if 
  you want to know how many times an error message appeared in a log file.


## -l: Print Matched Files

[freeCodeCamp](https://www.freecodecamp.org/news/grep-command-in-linux-usage-options-and-syntax-examples)

Example 1:

```grep -l "terrorist" ./technical/911report/*```

`./technical/911report/chapter-1.txt
./technical/911report/chapter-10.txt
./technical/911report/chapter-11.txt
./technical/911report/chapter-12.txt
./technical/911report/chapter-13.1.txt
./technical/911report/chapter-13.2.txt
./technical/911report/chapter-13.3.txt
./technical/911report/chapter-13.4.txt
./technical/911report/chapter-13.5.txt
./technical/911report/chapter-2.txt
./technical/911report/chapter-3.txt
./technical/911report/chapter-5.txt
./technical/911report/chapter-6.txt
./technical/911report/chapter-7.txt
./technical/911report/chapter-8.txt
./technical/911report/chapter-9.txt
./technical/911report/preface.txt`

  In this example, the `grep` command is searching for the string pattern "terrorist" in all the files under 
  the directory `/911report`. It's using the `-l` option, which searches the specified pattern in one file or 
  across multiple files or directories/subdirectories and displays all the file names that contain that 
  pattern. As shown in the output above, in this case, it displays the relative path to each file under the 
  `911report` directory. This command-line option is useful because it can narrow down which files contain the 
  specified string pattern you are looking for. 


Example 2:

```grep -l "DNA" ./technical/plos/*```

`./technical/plos/journal.pbio.0020013.txt
./technical/plos/journal.pbio.0020028.txt
./technical/plos/journal.pbio.0020035.txt
./technical/plos/journal.pbio.0020040.txt
./technical/plos/journal.pbio.0020043.txt
./technical/plos/journal.pbio.0020053.txt
./technical/plos/journal.pbio.0020067.txt
./technical/plos/journal.pbio.0020068.txt
./technical/plos/journal.pbio.0020071.txt
./technical/plos/journal.pbio.0020073.txt
./technical/plos/journal.pbio.0020121.txt
./technical/plos/journal.pbio.0020133.txt
./technical/plos/journal.pbio.0020145.txt
./technical/plos/journal.pbio.0020148.txt
./technical/plos/journal.pbio.0020150.txt
./technical/plos/journal.pbio.0020183.txt
./technical/plos/journal.pbio.0020190.txt
./technical/plos/journal.pbio.0020206.txt
./technical/plos/journal.pbio.0020213.txt
./technical/plos/journal.pbio.0020223.txt
./technical/plos/journal.pbio.0020241.txt
./technical/plos/journal.pbio.0020262.txt
./technical/plos/journal.pbio.0020263.txt
./technical/plos/journal.pbio.0020276.txt
./technical/plos/journal.pbio.0020302.txt
./technical/plos/journal.pbio.0020307.txt
./technical/plos/journal.pbio.0020347.txt
./technical/plos/journal.pbio.0020354.txt
./technical/plos/journal.pbio.0020400.txt
./technical/plos/journal.pbio.0020419.txt
./technical/plos/journal.pbio.0020431.txt
./technical/plos/journal.pbio.0020440.txt
./technical/plos/journal.pbio.0030024.txt
./technical/plos/journal.pbio.0030050.txt
./technical/plos/journal.pbio.0030056.txt
./technical/plos/journal.pbio.0030062.txt
./technical/plos/journal.pbio.0030065.txt
./technical/plos/journal.pbio.0030076.txt
./technical/plos/journal.pbio.0030094.txt
./technical/plos/journal.pbio.0030102.txt
./technical/plos/pmed.0010028.txt
./technical/plos/pmed.0010047.txt
./technical/plos/pmed.0020017.txt
./technical/plos/pmed.0020018.txt
./technical/plos/pmed.0020033.txt
./technical/plos/pmed.0020045.txt
./technical/plos/pmed.0020060.txt
./technical/plos/pmed.0020068.txt
./technical/plos/pmed.0020073.txt
./technical/plos/pmed.0020103.txt
./technical/plos/pmed.0020161.txt
./technical/plos/pmed.0020237.txt
./technical/plos/pmed.0020273.txt`

  In this example, the `grep` command is searching for the string pattern "DNA" in all the files under 
  the directory `/plos`. It's using the `-l` option, which searches the specified pattern in one file or 
  across multiple files or directories/subdirectories and displays all the file names that contain that 
  pattern. As shown in the output above, in this case, it displays the relative path to each file under the 
  `plos` directory. This command-line option is useful because it can narrow down which files contain the 
  specified string pattern you are looking for. 

