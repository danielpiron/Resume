# Daniel Piron
**Apps Dev Tech Lead Analyst**
Tel: 718-570-6310
e-mail: dannypiron@gmail.com

## Professional Summary
 * **Citigroup Derivatives Markets Inc. (CDMI), Jersey City, NJ** -
   ERA III - Application Test Utility Development and DevOps ~ *2019-Present*
 * **Citigroup Derivatives Markets Inc. (CDMI), Jersey City, NJ** -
   ERA II - Technical Lead/Architect for SDLC Tools Development ~ *2015-2019*
 * **Citigroup Derivatives Markets Inc. (CDMI), Jersey City, NJ** -
   ERA I - Software Configuration Management ~ *2005-2015*
 * **Sanrio International, Fort Lee, NJ** -
   Product Concept Art Design ~ *2004-2005*
 * **el-bohio.com, Queens, NY** -
   Web Design and Administration ~ *2001-2006*
 * **Opal Group, New York, NY** -
   Handheld Software Development ~ *May-July 2000*

## Strengths
 * Has a profound understanding of the design concepts of complex distributed
   systems and readily applies this knowledge to daily troubleshooting
   challenges.
 * Accustomed to and thrives in a high pressure and fast paced working
   environment with breakneck release cycles.
 * Skilled in C, C++, Python, and Objected-Oriented Perl, and is knowledgeable
   in cross-platform development.

## Technical Experience
* **Operating Systems** - Linux, MacOS, Solaris, Windows
* **Languages** - C++, Python, Perl, Bash, C, Javascript, Java, PHP, SQL,
                  Visual Basic, MOS 6502, x86 Assembler, MMX
* **Databases** - Oracle, PostgresSQL, MySQL, SQLite, Microsoft Access
* **DevOps Tools** - Git, Jira, Bitbucket, Jenkins, Artifactory, Teamcity, Docker, SonarCube, ITRS

## Education
**Queens College, CUNY - Computer Science Bachelors of Science** ~ *May 2002*

## Honors And Awards
 * Citi Gratitude Gold Award "Works as a Partner" (July 2020)
 * Citi Gratitude Copper Award "Works as a Partner" (February 2020)
 * Citigroup Award for Excellence in Performance (2006)
 * Graduated Cum Laude (2002)
 * Nucleus - Scientific Journal of Queens College, CUNY, Production/Layout
   Manager (2000-2002)
 * Golden Key Honor Society, Member (1999-2002)
 * Queens College Honors in Math and Natural Science, Member & IT Administrator
   (1998-2002)
 * Dean’s List (Fall 1997-Fall 1999, Spring 2001-Fall 2002)
 * Queens College Presidential Honors Award Recipient (1997)
 * Bertelsmann's "World of Expression" Scholarship, Fifth place in musical
   composition (1997)

## Experience

### Citigroup Derivatives Markets Incorporated (CDMI), Jersey City, NJ
**ERA III - Application Monitoring and Test Utility Development and DevOps** ~ *2015-Present*
 * Enhanced legacy trading application allowing it to run stand-alone (without
   a lab testing environment) by transparently mocking database, marketdata,
   quant, and user inputs requiring no modification to core components.
 * Designed test framework along with a scripting language for injecting inputs
   into trading applications and specifying assertions providing a stable
   foundation and confidence that errors would be found early and dealt with
   quickly.
 * Created regression test application for detecting inconistencies in quant
   code between releases of the application by replaying trades and reliability
   reproducing curve movement.
 * Designed C++ wrapper to ITRS monitoring XMLRPC API. This wrapper was
   subsequently used to report obscure performance statistics and was used to
   better allocate resources in production system. The wrapper was also shared
   with other groups through out Citi accelerating the efforts of other C++
   based teams to adopt ITRS as their monitoring system.
 * Built a daily release impact report combining data from Jira, Bitbucket, and
   our custom build system indicating which Jiras targeting were missing pull
   requests, which still had unmerged requests, and which applications were
   affected by which issues. This report provided tremendous transparency of
   the current state of the release for the Dev and QA teams.
 * Managed Jira, Bitbucket, Jenkins, Teamcity, SonarCube instances that were
   part of the DevOps infrastructure.
 * Tied Jira workflow to Bitbucket pull request approval and merge process
   promoting a consistent flow and clean hand-off between Dev and QA that
   succictly abided by all audit requirements.
 * Developed Docker based prototype build and runtime enviornments for
   application transitioning from Windows .NET to DotNET Core on Linux.
 * Adapted SonarCube reporting into custom builds workflow.

### Citigroup Derivatives Markets Incorporated (CDMI), Jersey City, NJ
**Technical Lead/Architect for SDLC Tools Development and DevOps** ~ *2015-2019*
 * Redesigned the Python rewrite of in-house multi-language (C++, C#, Java) and
   cross-platform (Windows & Linux) dependency management and build system,
   maintaining significant backwards compatibility with legacy system setting
   the stage for a Perforce to Git transition.
 * Promoted the use of Test Driven Development during Python rewrite
   significantly facilitating the implementation of complex changes to
   the code base.
 * Optimized initial step of build system dependency analysis reducing
   initialization times by 90% on average.
 * Lead effort to transition hundreds of developers from disparate teams
   and thousands of build artifacts from Perforce to Git.
 * Cleanly architected transition between disparate artifact storage on Windows
   and Linux to Artifactory resulting in zero downtime for users.
 * Maintained an open and friendly work environment with offshore talent,
   fostering a culture of personal growth and satisfaction where said talent
   often felt motivated to exceed expectations.
 * Conducted a weekly series of hour long educational sessions to provide
   training and insight to our tools and build process increasing user
   competence and satisfaction.

### Citigroup Derivatives Markets Incorporated (CDMI), Jersey City, NJ
**Software Configuration Management** ~ *2005-2015*
 * Unified nearly a dozen disparate builds, making up over 700 build artifacts,
   into a single continuously integrated process through the development of a
   makefile-free, multi-platform (Win32, Linux 32/64) and multi-language (C++,
   Managed C++, CSharp, Java) automated system (written in Perl) allowing users
   to add a new project to the build simply by checking in source and providing
   a list of required dependencies. This also facilated efforts to port
   applications from Windows to Linux as the first step was to sipmly specify
   Linux as a platform.
 * Automated in-house code generation routines and seamlessly integrated them
   into our code management system replacing manually run ad hoc scripts
   previously maintained by individual developers eliminating 99% of build
   errors due to code generation.
 * Implemented a simple dependency filtering mechanism resulting a 40%
   decrease in build times by better targeting artifacts by platform. Further
   gains in performance were made by reducing the number of calls to the SCM by
   60% in selected processes.
 * Designed and developed a process for source control configuration, based on
   concepts of inheritance, allowing for the automated propagation of production
   configs to over a dozen development and QA environments, reducing the config
   set needed to properly maintain an environment from thousands of files to
   under 20.
 * Created custom bindings between the Perforce source control management system
   and TeamTrack (and later JIRA) issue tracking system(s) allowing management
   to tightly control developer check-in increasing the reliability, fidelity and
   transparency of the development cycle.
 * Consistently called upon to troubleshoot issues in development, QA, and
   Production environments going above and beyond expected duties using various
   tools including code comparison, debuggers and dependency analyzers.
 * Was tasked with migrating and adapting QA and Development laboratories to
   Citigroup’s SOE environment.
 * Supported releases to operations facilities in North America, EMEA, and
   APAC regions.
 * Achieved a high level of respected for creative thinking, reliability,
   integrity, wit, and charm.

### Sanrio International, Fort Lee, NJ
**Product Concept Art Design** - *2004-2005*

 * Designed concept art for products featuring the character Keroppi that have
   appeared on a variety of products including plush dolls, medical scrubs and
   bed sheets.

### el-bohio.com, Queens, NY
**Web Design and Photography** - *2001-2006*

 * Quality of work resulted in publications, such as The London Times, and
   various authors to request stock photo material from site.
 * Contributed material to website's archive of world-class photography.

### Freelance Photo Retouch and Editing
**Photo retouch and editing** - *2002-2005*
 * Removed artifacts, scratches, discolorations, rips.
 * Seamlessly merged torn photographs.
 * Colorized black & white photos.

### Opal Group, New York, NY
**PalmOS Software Development** - *May-July 2000*

 * Designed and development a high performance HTML interpreter in C for PalmOS
   intended for the viewing and dissemination of conference agendas.
 * As sole software developer, was responsible for the research, design,
   development, testing and maintenance of PalmOS based technologies.
 * Performed minor HTML corrections to company web page and building
   workstations.

## Additional Skills
 * Excellent interpersonal and communication skills.
 * Exemplary writing ability.
 * Natural public speaker.
 * Bilingual; Fluent in English and Spanish.

## Fun Facts
 * As a self taught musical composer, created and orchestrated an original
   bridal chorus “Veronica Enters” for his own wedding.
 * Lists greatest achievement as having become a homeowner, husband, and
   father all within the span of a year.
 * Has been flying remote controlled model airplanes with father, as a hobby,
   since the age of 8, serving as the de facto pilot for maiden flights.

## References
*Available upon request*
