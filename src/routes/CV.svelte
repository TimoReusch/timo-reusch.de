<script>
    import SectionContainer from "$lib/components/SectionContainer.svelte";
</script>

<section class="resume background_gpattern" id="resume">
    <SectionContainer title="Resumé" backgroundText="Experience">
        <div class="row mt-4">
            <div class="col-lg">
                <ul class="list-inline resume-list">
                    <li>
                        <h4 class="mb-2"><a href="https://www.informatik.uni-wuerzburg.de" class="company-link"
                                            target="_blank">Julius-Maximilians-Universiät
                            Würzburg</a> - Student Research Assistant @ Chair of computer science X
                        </h4>
                        <span class="time">Sept. 2022 - now</span>
                        <p class="my-2">Detecting anomalies in huge datasets is a challenging task. Even if you
                            have managed to train a fairly accurate model, there will eventually be data points
                            where the model is unsure how to classify them. To improve it, experts
                            should review those data points and annotate them. These annotations are then stored
                            and taken into account in the subsequent training of the model.
                            For this use case, my job is to create a web-application (FastAPI, SvelteKit), that
                            experts can use to annotate those data points without having any knowledge in
                            machine learning at all. This involves a user- and role-management, as well as a
                            highly customizable interface for the annotation process.
                        </p>
                    </li>

                    <li>
                        <h4 class="mb-2"><a href="https://bb-net.de" class="company-link" target="_blank">bb-net
                            media GmbH</a>
                        </h4>
                        <span class="time">Jan. 2020 - Sept. 2022</span>
                        <ul class="list-inline resume-list my-3">
                            <li>
                                <h4 class="mb-2">Project Manager / Software Developer
                                </h4>
                                <span class="time">June 2021 - Sept. 2022</span>
                                <p class="my-2">bb-net uses their own software called "SAM" to automate big
                                    parts of the refurbishment process. SAM carries out all partial processing
                                    steps automatically and gives the employee special guidance through the
                                    whole process. The software started as a small script that grew a lot over
                                    time, which now results in issues in terms of scaling and complexity, why
                                    EOL is expected in the next few years.<br> My job was to
                                    plan and carry out the re-development of the whole architecture. This
                                    involved migrating the whole codebase from VBS to Java, redesigning the
                                    relational database and planning a highly scalable server infrastructure
                                    based on Spring Boot.<br>
                                    I was responsible for the project management and also coded along, working
                                    with various web technologies, Swift and of course Java.
                                </p>
                            </li>
                            <li style="padding-bottom: 0">
                                <h4 class="mb-2">Software Developer</h4>
                                <span class="time">Jan. 2020 - June 2021</span>
                                <p class="my-2">Working with web technologies (HTML, CSS, JavaScript, PHP) on
                                    the company's own ERP system and online shop, where I developed a few new
                                    features (like the creation of 360° images and their display in the online
                                    shop).
                                    <br> Furthermore, I gave various outdated web-frontends a fresh coat of
                                    paint, which included a mobile-first approach, complete redesign and SEO.
                                </p>
                            </li>
                        </ul>
                    </li>
                    <li style="padding-bottom: 0;">
                        <h4 class="mb-2"><a href="https://www.sap.com/germany/index.html" class="company-link"
                                            target="_blank">SAP SE</a>
                        </h4>
                        <span class="time">Sept. 2018 - Sept. 2019</span>
                        <ul class="list-inline resume-list my-3">
                            <li>
                                <h4 class="mb-2">Software Developer @ Next Level IT Labs & Experiences
                                </h4>
                                <span class="time">Jan. 2019 - Sep. 2019</span>
                                <p class="my-2 mb-4">
                                    I worked at the SAP IT division, which takes care of the internal IT of the
                                    company. There I joined a project called "SAP IT Showroom" within the "Next
                                    Level IT Lab and Experiences" subdivision.<br> Next
                                    Level IT Lab is building IT Showrooms at SAP Locations worldwide, to
                                    showcase how SAP is transforming into an intelligent enterprise with a
                                    future workplace. Within the Showrooms, visitors can discover products
                                    and tools from SAP, understand technologies and their impact on daily work
                                    and leverage tools and technologies to increase productivity.
                                </p>
                                <a href="https://youtu.be/GGLmQNO2uPE" target="_blank"
                                   class="btn btn-outline-primary btn-small">
                                    Have a closer look at the showroom
                                </a>
                                <p>
                                    <br> During my time there, we planned and opened the first ever IT Showroom
                                    at the headquarters in Walldorf. <br> Before the opening, I was involved in
                                    creating the frontend for the Stations, using Angular.
                                    After the opening, I supported the daily showroom business, which included
                                    answering technical questions of our colleagues, fixing bugs, documenting
                                    best practices, coordination with the partially external
                                    showroom staff and giving tours for the main showroom, as well as the
                                    VR/AR-Showroom. <br> My main project however became the creation of an
                                    e-learning solution to train tour guides for the Showroom, which
                                    is globally used by today.<br>
                                </p>
                            </li>
                            <li>
                                <h4 class="mb-2">Project lead: Imagefilm @ VT
                                </h4>
                                <span class="time">Jan. 2019 - Sept. 2019</span>
                                <p class="my-2">As a team of students, we created a concept for a new VT
                                    commercial and produced it. The end result can be watched on YouTube and
                                    sap.de/ausbildung
                                </p>

                                <a href="https://youtu.be/9Ee8QmSTj58" target="_blank"
                                   class="btn btn-outline-primary btn-small mt-3">
                                    Watch the commercial
                                </a>

                            </li>
                            <li style="padding-bottom: 0;">
                                <h4 class="mb-2">Corporate Student</h4>
                                <span class="time">Sept. 2018 - Sept. 2019</span>
                                <p class="my-2"> While being employed at SAPs headquarters in Walldorf, Germany
                                    as a corporate student, I attended classes at the Corporate State University
                                    Baden-Württemberg in Mannheim (Business Informatics focused on Sales
                                    & Consulting, B.Sc.), worked at a division (SAP IT) and took part in the
                                    following projects for the VT-Department:<br> - Realizing an Android app (Java)
                                    concept & prototype for accessing SAP facilities with your
                                    smartphone during a hackathon<br> - Content creation for SAPs social media
                                    channels
                                    <br> - Attending various trainings for project management, agile software
                                    development, User Experience & UI-Design, ABAP-Development
                                </p>
                            </li>
                        </ul>
                    </li>
                    <li></li>
                </ul>
            </div>
        </div>
    </SectionContainer>
</section>

<style lang="scss">
  section.resume {
    h3 {
      font-size: 1.5em;
    }
  }

  .resume-list {
    li {
      position: relative;
      padding: 0 15px 50px 40px;
    }

    li:before {
      content: "";
      width: 16px;
      height: 16px;
      border-radius: 50%;
      position: absolute;
      left: 3px;
      top: 4px;
    }

    li:after {
      content: "";
      position: absolute;
    }

    li:last-child:after {
      content: none;
    }
    h4 {
      font-size: 18px;
      font-family: inherit;
    }

    span.time {
      font-size: 0.875em;
      opacity: 1;
    }
  }

  .skill {
    .skill-icon {
      font-size: 2.7em;
      min-width: 60px;
    }
    .progresss-info span {
      font-size: 16px;
    }
    .progress {
      height: 6px;
      border-radius: 0;
      padding: 2px;
    }

    .progress-bar {
      width: 0;
      transition: all 1.5s ease-in-out;
    }
  }
</style>