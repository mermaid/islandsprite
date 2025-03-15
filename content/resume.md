+++
title = "Résumé"
+++

<style>
    :root {
        --border-color: #ddd;
    }
    .resume {
        /* display: flex; */
    }

    .section {
        margin: 0.5rem 0;
    }
    
    .section:first-of-type {
        padding-top: 0;
        margin-bottom: -0.75rem;
    }

    .centered-row {
        display: flex;
        justify-content: space-between;
        align-items: top;
        width: 100%;
    }

    .centered-row > * {
        flex: 1 1 0px;
        text-align: center;
    }

    .centered-row > *:last-child {
        text-align: end;
    }

    .centered-row > *:first-child {
        text-align: start;
    }

    .header-row {
        font-weight: bold;
        margin-top: 0.5rem;
    }

    .section .header-row:first-of-type {
        margin-top: 0;
    }

    #content .resume hr,
    #content .resume h4,
    #content .resume h3,
    #content .resume h2 {
        margin: 0;
    }

    #content .resume ul {
      list-style-position: outside;
      margin-left: 1.75rem;
      margin-top: 0.2rem;
      margin-bottom: 0.2rem;
    }
    
    #content .resume li {
      margin-bottom: 0.1rem;
    }
    
    .specific {
      font-style: italic;
      margin-bottom: 0.2rem;
      display: block;
    }

    @media print
    {    
        body > * {
            display: none;
        }
        body > #content {
            display: block !important;
        }
    }

    /* Add this new CSS for the connecting line */
    .header-row {
        position: relative;
    }
    
    .header-row .separator {
        height: 1px;
        background-color: var(--border-color);
        flex-grow: 100;
        align-self: center;
        margin: 0 1rem;
    }

    hr {
        border-color: var(--border-color);
    }
    
    /* Make text appear above the line */
    .header-row span {
        white-space: nowrap;
    }
</style>

<div class='resume'>
    <div class='section'>
        <div class='centered-row'>
            <h2>Cameron Holiman</h2>
            <span>
                <div><a href='https://github.com/mermaid'>@mermaid</a> on GitHub</div>
                <div><a href='https://islandsprite.com'>islandsprite.com</a></div>
                <div><a href='https://www.linkedin.com/in/cameron-holiman-a186718b/'>LinkedIn</a></div>
            </span>
        </div>
    </div>
    <div class='section'>
        <h4>Employment</h4>
        <hr />
        <div class='centered-row header-row role'>
            <span>Provo, UT</span>
            <span>Qualtrics</span>
            <span>2014 - Present</span>
        </div>
        <div class='centered-row header-row'>
            <span>Staff Software Engineer / Team Lead</span>
            <span class="separator"></span>
            <span>2025 - Present</span>
        </div>
        <ul>
            <li>Lead Design Office Hours sessions to accelerate product development across Engineering Research organization.</li>
            <li>Rearchitected database & file storage for Qualitative video tools enabling customer-managed encryption, resulting in enhanced security compliance, and allowed for significant increase in the number of customers who can utilize the products.</li>
        </ul>
        <div class='centered-row header-row'>
            <span>Senior Software Engineer / Team Lead</span>
            <span class="separator"></span>
            <span>2022 - 2025</span>
        </div>
        <span class="specific">Qualitative Research & Video Analysis Tools</span>
        <ul>
          <li>Lead a team of 4 engineers to build a comprehensive suite of Qualitative video research products from the ground up.</li>
          <li>Created custom video playback controls and online video editor for analysis, clipping, editing, and assembling highlight reels with high accessibility and performance.</li>
          <li>Developed in-house solutions for video processing, storage, editing, and streaming with a high focus on cost efficiency, resulting in an extremely profitable product (99%+ profit margin in some cases) that has driven many millions of dollars in revenue.</li>
          <li>Developed migration tools designed to help Qualtrics win customers and migrate them from competitors.</li>
        </ul>
        <span class="specific">Legacy Product Transformation</span>
        <ul>
          <li>Through targeted quarterly analysis and investments over 3 years, reduced customer issues by 50%, increased usage by 3000%, and decreased issue rate by 90%</li>
          <li>Added necessary metrics and tracking on product usage to guide improvements</li>
        </ul>
        <span class="specific">Subject Matter Expert</span>
        <ul>
          <li>Work as AWS subject matter expert across Qualtrics research organization, assisting teams and individuals with architecture, best practices, and training</li>
        </ul>
        <div class='centered-row header-row'>
            <span>Software Engineer I & II</span>
            <span class="separator"></span>
            <span>2016 - 2022</span>
        </div>
        <span class="specific">Qualtrics Survey Engine</span>
        <ul>
            <li>Helped develop the new Qualtrics Survey Engine, to replace the legacy engine.</li>
            <li>Created new hub-spoke architecture for the Survey Engine, allowing surveys to be delivered from any spoke datacenter worldwide.</li>
            <li>Sucecessfully increased reliability (100% uptime some quarters), faster delivery through worldwide distribution, and larger scale (10M+ respondents per day).</li>
            <li>Primary developer responsible for the final deprecation of the legacy Survey Engine.</li>
        </ul>
        <div class='centered-row header-row'>
            <span>QE Engineer</span>
            <span class="separator"></span>
            <span>2014 - 2016</span>
        </div>
        <span class="specific">Qualtrics Survey Engine</span>
        <ul>
            <li>Responsible for testing & validating the UI & Backend of the Legacy Qualtrics Survey Engine and it's migration to the new Survey Engine.</li>
            <li>Developed framework to enable the creation of E2E tests for the Survey Engine to validate features & survey combitibility between both engines.</li>
        </ul>
        <br />
        <div class='centered-row header-row'>
            <span>Utah</span>
            <span>Island Sprite, LLC</span>
            <span>2020 - Present</span>
        </div>
        <span class="specific">Creating applications for the iOS app store. Designed, developed, maintained by me.</div>
        <ul>
            <li><a href="https://plantir.app">Plantir:</a> Application for tracking & scheduling tasks plant owners</li>
            <li><a href="https://apps.apple.com/us/app/coffee-snob-stickers/id1154238768">Coffee Snob Stickers:</a> iMessage sticker app featuring coffee equipment</li>
        </ul>
        <div class='section'>
        <h4>Education</h4>
        <hr />
        <div class='centered-row header-row role'>
            <span>Cedar City, UT</span>
            <span>Southern Utah University</span>
            <span>2010 - 2014</span>
        </div>
        <ul>
            <li><b>Major:</b> Bachelor of Science in Computer Science. GPA 3.9</li>
        </ul>
    </div>
    <div class='section'>
        <h4>Tools & Technologies</h4>
        <hr />
        <ul>
            <li><b>Languages & Frameworks:</b> JavaScript, TypeScript, Node.js, React, Golang, Swift, SwiftUI, Objective-C, Java</li>
            <li><b>Cloud & Infrastructure:</b> AWS (DynamoDB, S3, MediaConvert, SQS, SNS, Lambda, CloudWatch, EC2, Elastic Beanstalk), Terraform, Docker, Kubernetes, Jenkins, Git, Gitlab</li>
        </ul>
    </div>
    <div class='section'>
        <h4>Patents</h4>
        <hr />
        <ul>
            <li><a href="https://patents.google.com/patent/US10049085B2/en">US 10,049,085</a>: Presenting views of an electronic document</li>
            <li><a href="https://patents.google.com/patent/US10521503B2/en">US 10,521,503</a>: Authenticating a respondent to an electronic survey</li>
            <li><a href="https://patents.google.com/patent/US11392970B2/en">US 11,392,970</a>: Administering a digital survey over voice-capable devices</li>
        </ul>
    </div>
    </div>
</div>

