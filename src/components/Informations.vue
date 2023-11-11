<script setup>
import InformationItem from './InformationItem.vue'
import AboutMeIcon from './icons/IconAboutMe.vue'
import ExperienceIcon from './icons/IconExperience.vue'
import SkillIcon from './icons/IconSkill.vue'
import ProjectsIcon from './icons/IconProjects.vue'
import ContactsIcon from './icons/IconContacts.vue'
</script>

<template>
  <InformationItem>
    <template #icon>
      <AboutMeIcon />
    </template>
    <template #heading>About Me</template>
    Hi, I'm Cristhian. A student, developer, and IT technician passionate about computer science. Eager for challenges, I constantly seek opportunities to enhance my skills in programming. With experience in independent and team 
    <a href="#" target="_blank" rel="noopener">projects</a>
    using Java, Vue, Quasar, Golang, and Node.
  </InformationItem>

  <InformationItem>
    <template #icon>
      <ExperienceIcon />
    </template>
    <template #heading>Work Experience</template>
    ✶ IT Support @ <a href="https://atlantic-technologies.com/it/" target="_blank" rel="noopener">Atlantic Technologies</a> > Apr 2023 - Present
    <br/>
    Activities: Technical Support, Google Suite, Software/Hardware Installation, Computer Repair, Network Management
    <br/>
    ✶ IT Intern @ <a href="https://comune.sedriano.mi.it/" target="_blank" rel="noopener">Comune di Sedriano</a> > Sep 2020 - Jun 2021
    <br/>
    Activities: Assisted system administrator at the CED. Responsibilities included software and hardware support at key municipal buildings and computer maintenance.
  </InformationItem>

  <InformationItem>
    <template #icon>
      <SkillIcon />
    </template>
    <template #heading>Skills</template>
    Programming Languages: <span class="highlight">Java, Vue, Quasar, Golang, Node</span><br/>
    Database Management: <span class="highlight">MySQL, PostgreSQL</span><br/>
    Code Maintenance: <span class="highlight">Git, GitHub</span>
  </InformationItem>

  <InformationItem>
    <template #icon>
      <ProjectsIcon />
    </template>
    <template #heading>Projects</template>
    You can find every non-commercial project I've made on my <a href="https://github.com/CristhianPeverelli/" target="_blank" rel="noopener">GitHub</a>.
  </InformationItem>

  <InformationItem>
    <template #icon>
      <ContactsIcon />
    </template>
    <template #heading>Contact Me</template>

    Email: cristhian.peverelli@gmail.com <br/>
    <a href="https://www.linkedin.com/in/cristhian-peverelli/" target="_blank" rel="noopener">LinkedIn</a> <br/>
    <a href="https://www.codewars.com/users/CristhianPeverelli" target="_blank" rel="noopener">CodeWars</a>
  </InformationItem>
</template>
