---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
  .container {
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    margin-top: 0; /* Remove any unintended top margin */
    padding-top: 0; /* Remove extra padding */
  }

  .content {
    flex: 2; /* Main content takes up more space */
    margin-top: 0; /* Ensure no extra top space */
    padding-top: 0;
  }

  .sidebar {
    flex: 1; /* Sidebar takes up less space */
    margin-left: 20px; /* Add spacing between the content and sidebar */
    margin-top: 0; /* Ensure sidebar aligns properly */
    padding-top: 0;
  }

  .sidebar iframe {
    display: block;
    margin-bottom: 10px; /* Adds spacing between iframes */
  }

  /* Reset margin/padding for body and container */
  body, html {
    margin: 0;
    padding: 0;
  }

  /* Responsive Design */
  @media (max-width: 768px) {
    .container {
      flex-direction: column;
    }
    .sidebar {
      margin-left: 0;
      margin-top: 20px; /* Stack sidebar below content on small screens */
    }
  }

  .page__content {
    margin-top: 0 !important;  /* Remove extra top margin */
    padding-top: 0 !important; /* Remove extra top padding */
}

.main {
    margin-top: 0 !important;
    padding-top: 0 !important;
}

  .wrapper {
    padding-top: 0 !important;
    margin-top: 0 !important;
}

.page {
    margin-top: 0 !important;
    padding-top: 0 !important;
}

  .author__profile {
    margin-top: 0 !important;
    padding-top: 0 !important;
}
</style>

<div class="container">
  <div class="content">
    <p>Welcome! I am a PhD candidate in the Department of Political Science at the University of California, Los Angeles, where I specialise in International Relations. I earned my <a href="https://cir.uchicago.edu/">MA</a> in International Relations from the University of Chicago and <a href="https://ppaweb.hku.hk/">BSocSc</a> in Politics and Public Administration from the University of Hong Kong.</p>

    <p>My <a href="http://shinghon.github.io/research">upcoming research</a> explores the influence of member states in international organisations, with focus on China using computational text analysis. I have <a href="http://shinghon.github.io/publications">published</a> in <i>International Affairs</i>, <i>Journal of Global Security Studies</i>, and written in <i>The Washington Post</i>. Prior to PhD, I interned at ALPHA Toronto, an Indonesian fair trade <a href="https://therainforestcoffee.wordpress.com/">co-op</a>, East Asian Institute NUS, and UNDP China.</p>
  </div>

  <div class="sidebar">
    <iframe height="454" width="325" frameborder='0' allowtransparency='true' scrolling='yes' 
            src='https://www.strava.com/athletes/74309136/latest-rides/95f0d6ad23cf1c5409b240d3330509fb9b90feab'></iframe>
    
    <iframe height="160" width="325" frameborder='0' allowtransparency='true' scrolling='no' 
            src='https://www.strava.com/athletes/74309136/activity-summary/95f0d6ad23cf1c5409b240d3330509fb9b90feab'></iframe>
  </div>
</div>
