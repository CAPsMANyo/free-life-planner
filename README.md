1. [The FREE LIFE PLANNER (FLP)](#the-free-life-planner-flp)
2. [Types of Problems](#types-of-problems)
3. [Expected User Base](#expected-user-base)
4. [Links](#links)
5. [A Few Screenshots](#a-few-screenshots)
6. [FLP Subsystems](#flp-subsystems)

## The FREE LIFE PLANNER (FLP)

This page will soon be deprecated.  To see the new (under construction) pages for FLP:

https://github.com/aindilis/flp/blob/main/ReferenceManual.md

https://github.com/aindilis/flp


The FRDCSA project has collected many A.I. tools and is working to
apply them toward planning for day-to-day life.  (There is a VM
containing the core systems:
https://github.com/aindilis/frdcsa-panoply-git-20200329 ). Sometimes
people are blindsided by things they didn't expect (and if they are
already struggling, it can be a serious problem). The Free Life
Planner (FLP) is trying to gather information that applies to us, such
as legal, financial, common sense, etc, and put that information into
a system that can reason and plan with it. One could put their goals
into the FLP and it should factor everything in and attempt to create
a plan.

Artificial intelligence involves problem-solving, and in order for
A.I. software to problem-solve it must grow larger in proportion to
problems and their complexity.  The FRDCSA has taken all these
codebases and "glued" everything together and made it available from
Emacs, Perl and Prolog (with APIs to other systems).  FLP applies this
directly towards helping users in their day-to-day lives. It contains
a large collection of things like planners and game-playing programs
(similar to AlphaZero), and applies them to common problems such as
finances, meal-planning, transportation, health care, etc.

FLP is similar to a personal planner, a personal information manager,
a home automation system, etc. It is designed with the disadvantaged
in mind, but is generally useful. Please note that the
free-life-planner GitHub repository does not contain the whole FLP
system, which is spread throughout all the FRDCSA codebases, and it
cannot run without them. (We are attempting to build an installer, but
it's not ready: https://github.com/aindilis/frdcsa-installer ).

FLP tries to get on top of food security, financial security,
emotional security, etc, using many different methods, and aiming at
different time frames and levels of detail. It tries to keep a digital
twin of the user and apply the gathered life-planning information to
their situation.

## Types of Problems

Here are some examples of planning and management problems:

+ Remembering to take the trash out before the trash truck arrives.

+ Getting an automatic notification to stock up on groceries before a
predicted storm hits, including the list of the groceries you need.

+ Remembering that when you finish filling out some particular
paperwork, to send a copy to your doctor.

+ Remember what the doctors instructions were, in a paperless office
with Machine Comprehension software, and helping you to conform to them.

+ Reminding you to work on your taxes, and to change your air filter.

+ Telling you that a particular plan of yours violates various moral
and ethical constraints.

+ Generating a complex monthly financial plan with contingencies for
unexpected expenses and if certain income doesn't come through.


## Expected User Base

There are few user bases that should benefit more from this system
than others:

+ People with disabilities such as pervasive developmental disorders.

+ People in poverty who are one misstep from disaster.

+ People with unwieldy illnesses.

+ People who are homeless.

+ People experiencing relationship violence.

+ Returning citizens.

There are special modules for each of these situations.


## Links

Here is the beginning of a replacement README.md (and Manual/etc) for this page (free-life-planner).

https://github.com/aindilis/flp


Here is the release of FRDCSA Panoply Git VM (containing older and stripped down versions of FRDCSA and Free Life Planner):

https://github.com/aindilis/frdcsa-panoply-git-20200329


Here is a story describing the Free Life Planner:

https://frdcsa.org/~andrewdo/writings/homeless-story.html


Here is the most recent talk on FLP.

https://ontologforum.org/index.php/ConferenceCall_2022_04_20


Here is the beginning of the release of FRDCSA (marking the Panoply release the official public release and deeming the last five years of work the "private" version of FRDCSA, and backporting from private to public as able):

https://github.com/aindilis/frdcsa-installer


Here is a recent talk from EmacsConf2019 about FRDCSA/FLP/Panoply:

https://frdcsa.org/~andrewdo/frdcsa-emacsconf2019-final.webm


Here is an independent codebase (no dependencies on FRDCSA) for interactive plan monitoring:

https://github.com/aindilis/plan-monitor


Here is some more recent work on the Interactive Execution Monitor:

https://frdcsa.org/~andrewdo/iem2-2.mp4

https://frdcsa.org/~andrewdo/iem2-3.mp4


Here is recent work on the Executive Function Assistant:

https://frdcsa.org/~andrewdo/executive-function-assistant.mp4


Here is a video of an older, much smaller and simpler version of the FLP
booting up (be careful, noisy):

https://www.youtube.com/watch?v=t_dCAlf26LE


Here is the beginning of a paper on FLP:

https://frdcsa.org/~andrewdo/pioneer/wk1/flp.pdf


and one on FRDCSA:

https://frdcsa.org/~andrewdo/pioneer/wk1/frdcsa.pdf


Here is a paper on the SPSE2 subsystem, an early planning system for
FRDCSA which inspired parts of FLP:

https://frdcsa.org/visual-aid/pdf/Temporal-Planning-and-Inferencing-for-Personal-Task-Management-with-SPSE2.pdf


Here is a link to the financial planning submodule:

https://github.com/aindilis/financial-planning#projected-transactions-for-florence-tucker


Here is a link to the meal planning submodule:

https://frdcsa.org/~andrewdo/WebWiki/MealPlanningResources.html


Here is a video which shows some progress on the planner systems and also later the meal planner:

https://www.youtube.com/watch?v=XZh_tHNboCI&t=15s


Here are some earlier documents about the FLP:

https://frdcsa.org/~andrewdo/writings/News-Challenge-2.html

https://frdcsa.org/~andrewdo/WebWiki/FreeLifePlanningCoachSoftware.html

https://frdcsa.org/~andrewdo/WebWiki/FreeLifePlanningCoachSoftwareUpdate.html

https://frdcsa.org/~andrewdo/WebWiki/FreeLifePlanner.html


Here is the README for Panoply/FRDCSA:

https://frdcsa.org/~andrewdo/writings/README.html


Here is the project blog:

https://facebook.com/frdcsa


Here is the LogicMOO system mentioned in the EmacsConf video, which FLP draws heavily upon and intends to integrate with eventually:

https://github.com/TeamSPoon/prologmud/wiki


And here the design docs for LogicMOO:

https://drive.google.com/drive/#folders/0B0QA19UX0ehlV1ZEaXEzc3hjTWM


## A Few Screenshots

There is more work finished than we can display here, because we are
"dogfooding" FLP.  It has much personal info unfit to be demoed, so we
can only show a few screenshots at present.

![flp-01](https://frdcsa.org/~andrewdo/projects/flp-screencaps/01.jpg)
![flp-02](https://frdcsa.org/~andrewdo/projects/flp-screencaps/02.jpg)
![flp-03](https://frdcsa.org/~andrewdo/projects/flp-screencaps/03.jpg)
![flp-04](https://frdcsa.org/~andrewdo/projects/flp-screencaps/04.jpg)
![flp-05](https://frdcsa.org/~andrewdo/projects/flp-screencaps/05.jpg)
![flp-06](https://frdcsa.org/~andrewdo/projects/flp-screencaps/06.jpg)
![flp-09](https://frdcsa.org/~andrewdo/projects/flp-screencaps/09.jpg)
![flp-10](https://frdcsa.org/~andrewdo/projects/flp-screencaps/10.jpg)
![flp-11](https://frdcsa.org/~andrewdo/projects/flp-screencaps/11.jpg)
![flp-12](https://frdcsa.org/~andrewdo/projects/flp-screencaps/12.jpg)
![flp-14](https://frdcsa.org/~andrewdo/projects/flp-screencaps/14.jpg)
![flp-16](https://frdcsa.org/~andrewdo/projects/flp-screencaps/16.jpg)
![flp-17](https://frdcsa.org/~andrewdo/projects/flp-screencaps/17.jpg)
![flp-18](https://frdcsa.org/~andrewdo/projects/flp-screencaps/18.jpg)
![flp-19](https://frdcsa.org/~andrewdo/projects/flp-screencaps/19.jpg)
![flp-20](https://frdcsa.org/~andrewdo/projects/flp-screencaps/20.jpg)
![flp-21](https://frdcsa.org/~andrewdo/projects/flp-screencaps/21.jpg)
![flp-22](https://frdcsa.org/~andrewdo/projects/flp-screencaps/22.jpg)
![flp-23](https://frdcsa.org/~andrewdo/projects/flp-screencaps/23.jpg)
![flp-25](https://frdcsa.org/~andrewdo/projects/flp-screencaps/25.jpg)
![flp-28](https://frdcsa.org/~andrewdo/projects/flp-screencaps/28.jpg)

## FLP Subsystems

<table>
<tr><td>alexaPushNotifications</td><td>Allows FLP to push notifications to the user using Alexas voice synthesis.</td></tr>
<tr><td>allTermAssertions</td><td>Lists all ist-Asserted instances of the term in the KB.</td></tr>
<tr><td>amazonTodoListIntegration</td><td>Integration with Alexa todo list.</td></tr>
<tr><td>argIsaDeduction</td><td>Infer types of objects from argIsa constraints, or vice versa.</td></tr>
<tr><td>atTimeUsingEventCalculus</td><td>Infer timelines for atTime predicates using Event Calculus.</td></tr>
<tr><td>automatedLegacyTesting</td><td>Automatically generate tests from dynamic traces of FLP systems, note changes in behavior that may indicate regressions.</td></tr>
<tr><td>autoprogramming</td><td>Allows FLP to edit software it is using.</td></tr>
<tr><td>billPaymentSubsystem</td><td>Tracks bills, when they are due, which have been paid, which are late, etc, etc.</td></tr>
<tr><td>bluetoothManagement</td><td>Manages integration with Bluetooth devices such as speakers.</td></tr>
<tr><td>calendricalRecurrences</td><td>Allows complex calendarical scheduling for plans, preconditions, recurrences, appointments, events etc.</td></tr>
<tr><td>choreCharting</td><td>Schedules who is working on what chores, which chores have still to be done.</td></tr>
<tr><td>constantNamesCapitalization</td><td></td></tr>
<tr><td>continuousIntegrationTesting</td><td>CI integration for FLP.</td></tr>
<tr><td>cycLIntegration</td><td>Converts between Prolog and CycL, allowing access to Cyc from within FLP'</td></tr>
<tr><td>cycloneBrowser</td><td>A browser for Cyclone, the version of PrologCYC/Pscyclone that is ported to FLP.</td></tr>
<tr><td>differentialAsserter</td><td>Allows FreeKBS2 to edit and quickly reload just the changed portions of large Contexts/Microtheories.</td></tr>
<tr><td>doConvertIntegration</td><td>Integrates an enormous repository of to.do lists from private FRDCSA systems into the FLP todo system.</td></tr>
<tr><td>domainEditor</td><td>Allows one to collect and edit all the relevant FLP facts that are referenced by a given PDDL planning domain.</td></tr>
<tr><td>eventCalculusPlanner</td><td>Abductive planner to infer context from measurements and rules.</td></tr>
<tr><td>fdssBankBalanceChecker</td><td>Financial Decision Support System module for pulling bank balance information.</td></tr>
<tr><td>financialPlanning</td><td>Does temporal metric contingency planning for finances, anticipates cash flow for recurring bills and payments in tight financial situations.</td></tr>
<tr><td>find</td><td>Tracks the location of a cell phone within the house by classifying WiFi signal strength.</td></tr>
<tr><td>fluxIntegrationWithSerproFFFOPCJulianAndPlanner</td><td>Allows FLUX Agent programming system to work with time and arbitrary Prolog terms.</td></tr>
<tr><td>googleHomeIntegration</td><td>Integrate with Google Home speech interface.</td></tr>
<tr><td>habituals</td><td>Helps keep track of habits.</td></tr>
<tr><td>homeAssistantIntegration</td><td>Integration with the Home-Assistant Smart Home system.</td></tr>
<tr><td>iem</td><td>Interactively walks user through completion of plans generated by FLP.</td></tr>
<tr><td>importExportOfPDDL</td><td>Allows conversion of PDDL to and from Prolog, including bidirectional translation of nested to nonnested terms.</td></tr>
<tr><td>importProblem</td><td>Allows the import of a PDDL problem file into the FLP logicbase.</td></tr>
<tr><td>inform7Parser</td><td>Able to parse and include Inform7 source files for world, behavior, rule etc modeling in FLP.</td></tr>
<tr><td>inform7Planner</td><td>Able to represent the world using an exact or similar model as the Inform7 system does, and plan over that world.</td></tr>
<tr><td>intakeSystem</td><td>Strategically and contingently interview new users to rapidly gain situational awareness in order to help strategize to meet their needs.</td></tr>
<tr><td>inventoryManagement</td><td>Carefully tracks personal inventory.</td></tr>
<tr><td>inventoryManagementInterface</td><td></td></tr>
<tr><td>kbGarbageCollection</td><td>Remove temporary nonessential information from the KB after a while.</td></tr>
<tr><td>kbMaintenance</td><td></td></tr>
<tr><td>kbfsFormalogGitBindings</td><td>Allows FLP to manage files within Git Repositories.</td></tr>
<tr><td>kbfsFormalogInotifyIntegration</td><td>Tracks and triggers on file system operations using iNotify and KBFS-Formalog.</td></tr>
<tr><td>kbs2DataIntegration</td><td>Persistnce through ODBC/SWIPL for FLP using MySQL.</td></tr>
<tr><td>kbs2MySQLPersistence</td><td>Persistence through UniLang/FreeKBS2 for FLP using MySQL.</td></tr>
<tr><td>kbs2ReasonerProlog</td><td>A backend for FreeKBS2 to use Prolog instead of Vampire-KIF, etc, as the reasoning engine.</td></tr>
<tr><td>lifeWorkflowSystem</td><td>Create "Business Processes" for real life autopoietic processes.</td></tr>
<tr><td>locationLogic</td><td>Reason with and trigger upon all locational aspects of the user from GPS and Wifi location tracking.</td></tr>
<tr><td>logicVerification</td><td>Uses model checkers to prove safety and liveliness properties of different logics.</td></tr>
<tr><td>mealPlanner</td><td>Comprehensive Meal Planning, able to track barcodes, suppliers, price, inventory, nutrition, recipes, preferences, etc.</td></tr>
<tr><td>medicationTrackingSystem</td><td>Track user medication, side effects, refills, renewals, appointments, inventory, etc.</td></tr>
<tr><td>mepkIntegration</td><td>Allows epistemic planning in FLP, useful for managing the situational awareness of users.</td></tr>
<tr><td>microtheories</td><td>Implements Cyc-like Microtheories for clean separation and inheritance of KB knowledge.</td></tr>
<tr><td>multiuserSupport</td><td>Allows FLP to support multiple users without cross-contamination of data.</td></tr>
<tr><td>musicPlayback</td><td>Manages music playback, controllable from Alexa.</td></tr>
<tr><td>mycroftIntegration</td><td>Integrate with MyCroft speech interface.</td></tr>
<tr><td>nagiosIntegration</td><td>Network monitoring integration (with Setanta) for defending the security of FLP and its private information store.</td></tr>
<tr><td>negation</td><td>Allows classical negation in Prolog, or negation with atTime.</td></tr>
<tr><td>nestedFormulaeForVerb</td><td></td></tr>
<tr><td>nestedTermToNonnestedTermMapper</td><td>Maps terms which have nonatomic subterms to and from terms that do not.</td></tr>
<tr><td>nlGeneration</td><td>Translates Prolog representations into English and other languages.</td></tr>
<tr><td>notificationsSystem</td><td>A notification system like Android notifications, for recurrences, plan steps, appointments and such.</td></tr>
<tr><td>objectDetectionIntegration</td><td>Detection and reasoning with objects and time in video surveillance feeds.</td></tr>
<tr><td>openAuth2</td><td>Ensure FCMS (FRDCSA CMS) can authenticate using OpenAuth2.</td></tr>
<tr><td>organizationalRules</td><td>A source code critic system to ensure FLP source files are structured correct and follow FLP best practices.</td></tr>
<tr><td>owntracks</td><td>Tracks the GPS location of the cell phone, does reverse GEO lookups'.</td></tr>
<tr><td>pantryManagementInterface</td><td>An inventory subinterface for handling food pantries and all the special functions they require.</td></tr>
<tr><td>pddlSWIPLPackage</td><td>A pack for SWIPL with PDDL functionality originally written for FLP.</td></tr>
<tr><td>planningDomains</td><td>Planning to maintain or regain contact with the user regardless of where the user is.</td></tr>
<tr><td>productivityInterview</td><td>Elicits information regarding which conditions of productivity are presently met, including planning for future meeting of needs.</td></tr>
<tr><td>productivityRequirements</td><td>Tracks the conditions for being productive, whether they are satisfied, and plans to satisfy and maintain them.</td></tr>
<tr><td>programSynthesis</td><td>Allows FLP to compose algorithms to solve problems it is facing.</td></tr>
<tr><td>prologToGdlConversion</td><td>Bidirectional converion from Prolog to GDL (Game Description Language) to allow GGP (General Game Playing) agents to solve life-games.</td></tr>
<tr><td>qlfPersistence</td><td>Move monotonic FLP FreeKBS2 Predicates/Contexts/Microtheories into QLF for faster loading, compression, and cold storage.</td></tr>
<tr><td>receiptManager</td><td>Tracks online downloaded or email and brick and mortar scanned receipts, pulls supplier and pricing information.</td></tr>
<tr><td>resourceManager</td><td>Tracks household resources, finances and productivity requirements.</td></tr>
<tr><td>securityPlanner</td><td>Generates adversarial plans to keep information/resources secure.</td></tr>
<tr><td>sensorIntegration</td><td>A generic interface for all manner of sensors to update the world-model of FLP.</td></tr>
<tr><td>shoppingList</td><td>Tracks complete lifecycle of resource acquisition.</td></tr>
<tr><td>speechInterface</td><td>A dialog system for interacting with FLP over Alexa, via text chat, or other modes.</td></tr>
<tr><td>temperatureMonitor</td><td>Integrates with USB or 433MHz temperature sensors and online weather APIs to track internal/external temperature, and take actions based on temperature changes/patterns.</td></tr>
<tr><td>temporalSemantics</td><td>Ability to reason with time information in Prolog using atTime, such as with the Event Calculus, PDDL temporal planning, or the Julian date time library.</td></tr>
<tr><td>universalParserBNFParser</td><td>Part of Prolog-Agent, needed to parse arbitrary program output, such as the output of top or ls, into semantic representations understable by FLP.</td></tr>
<tr><td>worldKnowledgePlusAutovivification</td><td>Tracks world knowledge such as names, ontological categories and so forth, making educated guesses as needed.</td></tr>
<tr><td>zoneMinderIntegration</td><td>Surveillance integration and special AI modules for video understanding.</td></tr>
</table>
