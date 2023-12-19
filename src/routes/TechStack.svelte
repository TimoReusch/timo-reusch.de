<script>
    import SectionContainer from "$lib/components/SectionContainer.svelte";
    import pythonLogo from "$lib/assets/images/logos/python.svg";
    import mariaDBLogo from "$lib/assets/images/logos/mariaDB.svg";
    import mavenLogo from "$lib/assets/images/logos/maven.svg";
    import abapLogo from "$lib/assets/images/logos/sap.svg";
    import sapUI5Logo from "$lib/assets/images/logos/sapui5.svg";
    import arduinoLogo from "$lib/assets/images/logos/arduino.svg";
    import azureDevOpsLogo from "$lib/assets/images/logos/azure_devops.png";
</script>

<section class="stack background_gpattern" id="stack">
    <SectionContainer title="What I Work With" backgroundText="Tech Stack">
        <div class="row">
            <div class="col">
                <h3 class="mt-5 mb-4">Currently working with</h3>
                <div class="row">
                    <div class="col-md-6">
                        <div class="row">
                            <div class="col">
                                <p>Languages</p>
                            </div>
                        </div>
                        <div class="row">
                            <div class="col-6">
                                <div class="iconContainer">
                                    <img src={pythonLogo} width="35"
                                         style="margin-right: 20px;">
                                    <span>Python</span>
                                </div>
                            </div>
                            <div class="col-6">
                                <div class="iconContainer">
                                    <span class="devicon-swift-plain colored icon"></span>
                                    <span>Swift</span>
                                </div>
                            </div>
                            <div class="col-6">
                                <div class="iconContainer">
                                    <span class="devicon-javascript-plain colored icon"></span>
                                    <span>JavaScript</span>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-6">
                        <div class="row">
                            <div class="col">
                                <p>Frameworks & Tools</p>
                            </div>
                        </div>
                        <div class="row">
                            <div class="col-6">
                                <div class="iconContainer">
                                    <span class="devicon-fastapi-plain colored icon"></span>
                                    <span>FastAPI</span>
                                </div>
                            </div>
                            <div class="col-6">
                                <div class="iconContainer">
                                    <span class="devicon-firebase-plain colored icon"></span>
                                    <span>Firebase</span>
                                </div>
                            </div>
                            <div class="col-6">
                                <div class="iconContainer">
                                    <span class="devicon-svelte-plain colored icon"></span>
                                    <span>Svelte</span>
                                </div>
                            </div>
                            <div class="col-6">
                                <div class="iconContainer">
                                    <span class="devicon-sass-original colored icon"></span>
                                    <span>SASS</span>
                                </div>
                            </div>
                            <div class="col-6">
                                <div class="iconContainer">
                                    <span class="devicon-bootstrap-plain icon"></span>
                                    <span>Bootstrap</span>
                                </div>
                            </div>
                            <div class="col-6">
                                <div class="iconContainer">
                                    <img src={mariaDBLogo} width="35"
                                         style="margin-right: 20px;">
                                    <span>MariaDB</span>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="row">
            <div class="col">
                <h3 class="mt-5 mb-4">Worked with before</h3>
                <div class="row">
                    <div class="col-md-6">
                        <div class="row">
                            <div class="col">
                                <p>I don't work with these technologies on a daily basis, but from time to time:
                                </p>
                            </div>
                        </div>
                        <div class="row">
                            <div class="col-6">
                                <div class="iconContainer">
                                    <span class="devicon-java-plain colored icon"></span>
                                    <span>Java</span>
                                </div>
                            </div>
                            <div class="col-6">
                                <div class="iconContainer">
                                    <span class="devicon-spring-plain colored icon"></span>
                                    <span>Spring</span>
                                </div>
                            </div>
                            <div class="col-6">
                                <div class="iconContainer">
								<span style="margin-right: 20px;">
									<img src={mavenLogo} width="35">
								</span>
                                    <span>Maven</span>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-6">
                        <div class="row">
                            <div class="col">
                                <p>I haven't used those in a while now, but did some projects in the past:
                                </p>
                            </div>
                        </div>
                        <div class="row">
                            <div class="col-6">
                                <div class="iconContainer">
                                    <img src={abapLogo} style="margin-right: 20px;">
                                    <span>ABAP</span>
                                </div>
                            </div>
                            <div class="col-6">
                                <div class="iconContainer">
                                    <img src={sapUI5Logo} style="margin-right: 25px;">
                                    <span>SAPUI5</span>
                                </div>
                            </div>
                            <div class="col-6">
                                <div class="iconContainer">
                                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/androidstudio/androidstudio-original.svg"
                                         width="35"
                                         style="margin-right: 20px; background-color: white; border-radius: 20px; padding: 4px;"/>
                                    <span>Android (Java)</span>
                                </div>
                            </div>
                            <div class="col-6">
                                <div class="iconContainer">
                                    <img src={arduinoLogo} style="margin-right: 25px;">
                                    <span>Arduino</span>
                                </div>
                            </div>
                            <div class="col-6">
                                <div class="iconContainer">
                                    <span class="devicon-php-plain colored icon"></span>
                                    <span>PHP</span>
                                </div>
                            </div>
                            <div class="col-6">
                                <div class="iconContainer">
                                    <span class="devicon-wordpress-plain colored icon"></span>
                                    <span>WordPress</span>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="section-content flex-grow-1">
            <div class="row">
                <div class="col">
                    <h3 class="mt-5 mb-4">DevOps</h3>
                    <div class="row gy-5">
                        <div class="col-6 col-md-3">
                            <div class="iconContainer">
                                <span class="devicon-git-plain colored icon"></span>
                                <span>Git</span>
                            </div>
                        </div>
                        <div class="col-6 col-md-3">
                            <div class="iconContainer">
                                <span class="devicon-github-original icon"></span>
                                <span>GitHub</span>
                            </div>
                        </div>
                        <div class="col-6 col-md-3">
                            <div class="iconContainer">
                                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/gitlab/gitlab-original.svg"
                                     width="35" style="margin-right: 20px;"/>
                                <span>GitLab</span>
                            </div>
                        </div>
                        <div class="col-6 col-md-3">
                            <div class="iconContainer">
                                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/googlecloud/googlecloud-original.svg"
                                     width="35" style="margin-right: 20px;"/>
                                <span>Google Cloud</span>
                            </div>
                        </div>
                        <div class="col-6 col-md-3">
                            <div class="iconContainer">
						<span style="margin-right: 20px;">
							<img src={azureDevOpsLogo} width="35">
						</span>
                                <span>Azure DevOps</span>
                            </div>
                        </div>
                        <div class="col-6 col-md-3">
                            <div class="iconContainer">
                                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/azure/azure-original.svg"
                                     width="33" style="margin-right: 20px;"/>
                                <span>Azure (Basics)</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
    </SectionContainer>
</section>