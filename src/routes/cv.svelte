<!-- src/routes/about.svelte -->
<svelte:head>
    <title>CV</title>
</svelte:head>

<div>
    <h1>CV</h1>

    <h2>In short</h2>
    <p>
        I’ve been in software engineering for since 2010, having worked
        extensively with front-end applications for the first 10 years. More
        recently I have been making a move towards back-end development, seeking
        to broaden my experience and deepen my knowledge within that area. I’ve
        had responsibilities as lead developer, team manager and technical
        program manager and tend to take on leadership roles, but my true
        interest lies in the creativity of technical solutions.
    </p>

    <h2>Experience</h2>

    <h3>BookBeat AB</h3>
    <h3 class="secondary">Senior software engineer</h3>
    <h4>JUNE 2019 – PRESENT, STOCKHOLM</h4>
    <p>
        BookBeat is an audio streaming service with about 120 employees. I
        joined BookBeat to make a journey back towards full-time software
        development, and more specifically to learn more backend. As somewhat of
        an internal gun-for-hire I've been taking on a multitude of
        responsibilities and technologies in different teams. Backend, migration
        to .NET Core, Kubernetes, changing CI tool, lead developer on new
        services and projects, interim team lead, and more. For most of my time
        here I've been working full-stack with everything from configuration of
        Traffic Managers in Azure, to database management, backend .NET
        development, frontend for several of internal and external web pages.
        BookBeat has no Ops team so everything is handled by us developers:
        deployments, monitoring, logging and support.
    </p>
    <p>
        Technologies used: .NET Core, EF Core, Kubernetes, Docker, Azure
        Pipelines, Octopus Deploy, React, Azure Service bus, Azure Storage bus,
        Helm, New Relic, MSSQL, RavenDB, Azure TableStorage, Azure CosmosDB,
        Jest, Playwright, xUnit, NUnit
    </p>

    <h3>Gametek AB (former Mr Green Technology AB)</h3>
    <h3 class="secondary">Technical program manager</h3>
    <h4>AUGUST 2018 - MAY 2019, STOCKHOLM</h4>

    <p>
        I got the chance to work in the Gametek management team as a technical
        program manager. My responsibilities were to plan how to advance the
        technical platform together with all tech leads and product owners in
        the organization, to make sure that we could meet future business
        demands while delivering a technologically top-of-the-line platform.
    </p>

    <h3 class="secondary">Lead front-end developer</h3>
    <h4>JULY 2015 - JULY 2018, Stockholm</h4>

    <p>
        I joined Mr Green Technology as an employee and front-end lead
        developer, being responsible for delivering the new SPA mobile-first
        web. In this position I focused a lot on making the delivery process
        fast - focusing on testing, code quality and code reusability.
        Technologies used: JavaScript, AngularJS, TeamCity, Docker, CSS3,
        Node.js, Karma, Jasmine
    </p>

    <h3 class="secondary">Front-end developer</h3>
    <h4>FEBRUARY 2014 - JUNE 2015, STOCKHOLM</h4>

    <p>
        Mr Green Technology is the development department of online casino Mr
        Green, at the time around 30 employees. After parental leave I joined Mr
        Green Technology as a frontend developer consultant. I worked with both
        the front-end and back-end for the mobile web. Shortly after, I was
        transferred to a new team spear-heading a new SPA frontend that was to
        replace both the desktop and mobile web pages.
    </p>
    <p>
        Technologies used: JavaScript, jQuery Mobile, C#.NET, TeamCity,
        AngularJS
    </p>

    <h3>Net Entertainment AB (via Netlight Consulting AB)</h3>
    <h3 class="secondary">Lead front-end developer</h3>
    <h4>APRIL 2011 - MAY 2013, STOCKHOLM</h4>
    <p>
        Net Entertainment is a highly successful gambling company, at the time
        around 150 employees in the tech department. In 2011 all of NetEnt’s
        games were based on Flash, but mobile gaming was growing fast and it was
        clear that Flash was never going to work on iPhones, thus NetEnt set out
        to find a replacement to keep an attractive offering. I was hired as a
        consultant and took the role of lead developer for a new JavaScript
        gaming team. I engineered the main framework for the gaming client which
        was based on rendering with CSS3 animations and HTML5 audio elements,
        both of which were highly experimental at the time. I continued with
        hiring and setting up more gaming teams, over time taking the role as
        scrum master and project manager for the JavaScript game releases, being
        responsible for planning the releases and making sure the teams
        delivered on time and with quality, while at the same time expanding and
        enhancing the gaming framework to support future games.
    </p>
    <p>Technologies used: JavaScript, CSS3, HTML5, Maven, Jenkins</p>

    <h3>Fido Film AB AB (now FTrack)</h3>
    <h3 class="secondary">Software engineer</h3>
    <h4>NOVEMBER 2010 - APRIL 2011, STOCKHOLM</h4>
    <p>
        My first job! It was hard to imagine I would be of any use when leaving
        university... All those years and all those studies, yet it felt as if
        we had nothing tangible to bring to an actual workplace! I worked at a
        special effects studio who were building their own Project and Asset
        Management tool. Frontend and backend.
    </p>
    <p>Technologies used: JavasScript ExtJS, Python, Jenkins</p>
</div>

<style>
    h4 {
        text-transform: uppercase;
        color: gray;
        margin-top: -14px;
        font-size: 14px;
        font-weight: normal;
    }

    .secondary {
        font-weight: normal;
    }
</style>
