<style>
/* Card Grid Container */
.card-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
  gap: 20px;
  margin: 30px 0;
}

/* Card Styling */
.card {
  border-radius: 8px;
  overflow: hidden;
  box-shadow: 0 4px 6px rgba(0,0,0,0.1);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
  background-color: #fff;
  height: 100%;
  display: flex;
  flex-direction: column;
}

.card:hover {
  transform: translateY(-5px);
  box-shadow: 0 10px 20px rgba(0,0,0,0.15);
}

/* Card Image Container */
.card-image {
  height: 160px;
  overflow: hidden;
  position: relative;
  background-color: #f5f5f5;
}

.card-image img {
  width: 100%;
  height: 100%;
  /* object-fit: cover; */
  transition: transform 0.3s ease;
}

.card:hover .card-image img {
  transform: scale(1.05);
}

/* NEW CLASS FOR PROJECT LOGO IMAGES */
.project-logo-image {
  object-fit: contain;
  width: 100%;
  height: 120px;
  background: #fff;
  padding: 12px;
  margin: 0 auto;
  display: block;
}

/* Profile Image */
.profile-image {
  position: absolute;
  bottom: -20px;
  left: 16px;
  width: 50px;
  height: 50px;
  border-radius: 50%;
  border: 3px solid white;
  background-color: #fff;
  overflow: hidden;
  box-shadow: 0 2px 4px rgba(0,0,0,0.1);
}

.profile-image img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}

/* Card Content */
.card-content {
  padding: 24px 16px 16px;
  flex-grow: 1;
  display: flex;
  flex-direction: column;
}

.card-title {
  margin-top: 0;
  margin-bottom: 8px;
  font-size: 1.2rem;
  font-weight: 600;
  color: #333;
}

.card-description {
  margin-bottom: 12px;
  color: #666;
  flex-grow: 1;
  font-style: italic;
}

/* Card Link */
.card a {
  text-decoration: none;
  color: inherit;
  display: block;
  height: 100%;
}

/* Tag Styling */
.card-tag {
  display: inline-block;
  background-color: #f0f0f0;
  color: #666;
  padding: 4px 8px;
  border-radius: 4px;
  font-size: 0.8rem;
  margin-right: 6px;
  margin-bottom: 6px;
  font-style: italic;
}

/* Contact Info */
.card-contact {
  font-size: 0.85rem;
  color: #888;
  margin-top: 8px;
  border-top: 1px solid #eee;
  padding-top: 8px;
}

.card-contact a {
  color: #4a86e8;
  display: inline;
}

/* NEW CSS STYLES FOR PROBLEM/SOLUTION & STATUS */
.card-section {
  margin-bottom: 12px;
}

.card-section h4 {
  margin-top: 0;
  margin-bottom: 4px;
  font-size: 0.95rem;
  font-weight: 700;
  color: #444;
}

.card-section p {
  font-size: 0.9rem;
  color: #666;
  margin-bottom: 0;
  font-style: normal;
}

.card-status-section {
  margin-bottom: 12px;
  font-size: 0.85rem;
  color: #555;
}

.card-status-label {
  font-weight: 600;
}

.card-status {
  font-style: italic;
  color: #777;
}
/* END NEW CSS STYLES */

/* Styling for the introductory content section */
.intro-content {
  margin-bottom: 20px; /* Add some space before the card grid */
}

.intro-content ul {
  list-style-type: disc;
  margin-top: 1em; /* Space above the list */
  margin-bottom: 1em; /* Space below the list */
  padding-left: 40px; /* Standard indentation for lists */
}

.intro-content li {
  margin-bottom: 0.5em; /* Space between list items */
}

/* Media Queries for Better Responsiveness */
@media (max-width: 600px) {
  .card-grid {
    grid-template-columns: 1fr;
  }
}
</style>
<div class="intro-content">
<p>Fellowship Prototypes represent original contributions to the field of political technology by our 2025 cohort. Each project addresses real-world civic challenges, creating infrastructural tools designed to be used by political, civic, or public sector communities.</p>

<p>The projects showcased here reflect our commitment to creating technology that is:</p>
<ul>
<li>Available to organizations regardless of political affiliation</li>
<li>Designed for real-world use by civic communities</li>
<li>Addressing gaps in existing civic infrastructure</li>
<li>Built with privacy, security, and accessibility in mind</li>
</ul>

<p>Each fellow has developed their project independently, with guidance from our faculty and input from potential user communities</p>
</div>

<div class="card-grid">
  <!-- Heather McRobie -->
  <div class="card">
    <a href="heather-project/">
      <div class="card-image">
        <img src="/images/newspeak-logo.png" alt="Heather's Project Screenshot" class="project-logo-image">
        <div class="profile-image">
          <img src="/images/Heather.jpeg" alt="Heather McRobie">
        </div>
      </div>
      <div class="card-content">
        <h3 class="card-title">Heather McRobie Allansdottir</h3>
        <p class="card-description">Coming soon...</p>
        <div class="card-section">
          <h4>Problem</h4>
          <p>Coming soon...</p>
        </div>
        <div class="card-section">
          <h4>Solution</h4>
          <p>Coming soon...</p>
        </div>
        <div class="card-status-section">
          <span class="card-status-label">Status:</span> <span class="card-status">Coming soon...</span>
        </div>
        <div>
          <span class="card-tag">Coming soon...</span>
        </div>
        <div class="card-contact">
          <a href="mailto:heather.allansdottir@gmail.com">Contact</a>
        </div>
      </div>
    </a>
  </div>
  <!-- Ollie Bream McIntosh -->
  <div class="card">
    <a href="ollie-project/">
      <div class="card-image">
        <img src="/images/newspeak-logo.png" alt="Ollie's Project Screenshot" class="project-logo-image">
        <div class="profile-image">
          <img src="/images/Ollie.jpeg" alt="Ollie Bream McIntosh">
        </div>
      </div>
      <div class="card-content">
        <h3 class="card-title">Ollie Bream McIntosh</h3>
        <p class="card-description">Coming soon...</p>
        <div class="card-section">
          <h4>Problem</h4>
          <p>Coming soon...</p>
        </div>
        <div class="card-section">
          <h4>Solution</h4>
          <p>Coming soon...</p>
        </div>
        <div class="card-status-section">
          <span class="card-status-label">Status:</span> <span class="card-status">Coming soon...</span>
        </div>
        <div>
          <span class="card-tag">Coming soon...</span>
        </div>
        <div class="card-contact">
          <a href="mailto:ollie@raincoatfish.com">Contact</a>
        </div>
      </div>
    </a>
  </div>
  <!-- Jyotsna Iyer -->
  <div class="card">
    <a href="jyo-project/">
      <div class="card-image">
        <img src="/images/newspeak-logo.png" alt="Jyotsna's Project Screenshot" class="project-logo-image">
        <div class="profile-image">
          <img src="/images/Jyo.jpeg" alt="Jyotsna Iyer">
        </div>
      </div>
      <div class="card-content">
        <h3 class="card-title">Jyotsna Iyer</h3>
        <p class="card-description">Coming soon...</p>
        <div class="card-section">
          <h4>Problem</h4>
          <p>Coming soon...</p>
        </div>
        <div class="card-section">
          <h4>Solution</h4>
          <p>Coming soon...</p>
        </div>
        <div class="card-status-section">
          <span class="card-status-label">Status:</span> <span class="card-status">Coming soon...</span>
        </div>
        <div>
          <span class="card-tag">Coming soon...</span>
        </div>
        <div class="card-contact">
          <a href="mailto:jyotsna.iy@gmail.com">Contact</a>
        </div>
      </div>
    </a>
  </div>
  <!-- Richard Kemp -->
  <div class="card">
    <a href="richard-project/">
      <div class="card-image">
      <div class="project-logo-image">
        <img src="/images/newspeak-logo.png" alt="Richard's Project Screenshot" class="project-logo-image">
        </div>
        <div class="profile-image">
          <img src="/images/Richard.jpeg" alt="Richard Kemp">
        </div>
      </div>
      <div class="card-content">
        <h3 class="card-title">Richard Kemp</h3>
        <p class="card-description">Coming soon...</p>
        <div class="card-section">
          <h4>Problem</h4>
          <p>Coming soon...</p>
        </div>
        <div class="card-section">
          <h4>Solution</h4>
          <p>Coming soon...</p>
        </div>
        <div class="card-status-section">
          <span class="card-status-label">Status:</span> <span class="card-status">Coming soon...</span>
        </div>
        <div>
          <span class="card-tag">Coming soon...</span>
        </div>
        <div class="card-contact">
          <a href="mailto:richardtkemp@gmail.com">Contact</a>
        </div>
      </div>
    </a>
  </div>
  <!-- Paulina Wisdom -->
  <div class="card">
    <a href="paulina-project/">
      <div class="card-image">
        <img src="/images/newspeak-logo.png" alt="Paulina's Project Screenshot" class="project-logo-image">
        <div class="profile-image">
          <img src="/images/Paulina.jpeg" alt="Paulina Wisdom">
        </div>
      </div>
      <div class="card-content">
        <h3 class="card-title">Paulina Wisdom</h3>
        <p class="card-description">Coming soon...</p>
        <div class="card-section">
          <h4>Problem</h4>
          <p>Coming soon...</p>
        </div>
        <div class="card-section">
          <h4>Solution</h4>
          <p>Coming soon...</p>
        </div>
        <div class="card-status-section">
          <span class="card-status-label">Status:</span> <span class="card-status">Coming soon...</span>
        </div>
        <div>
          <span class="card-tag">Coming soon...</span>
        </div>
        <div class="card-contact">
          <a href="mailto:paulina.wisdom@icloud.com">Contact</a>
        </div>
      </div>
    </a>
  </div>
  <!-- Ilya Mouzykantskii -->
  <div class="card">
    <a href="ilya-project/">
      <div class="card-image">
        <img src="/images/newspeak-logo.png" alt="Ilya's Project Screenshot" class="project-logo-image">
        <div class="profile-image">
          <img src="/images/Ilya.jpeg" alt="Ilya Mouzykantskii">
        </div>
      </div>
      <div class="card-content">
        <h3 class="card-title">Ilya Mouzykantskii</h3>
        <p class="card-description">Coming soon...</p>
        <div class="card-section">
          <h4>Problem</h4>
          <p>Coming soon...</p>
        </div>
        <div class="card-section">
          <h4>Solution</h4>
          <p>Coming soon...</p>
        </div>
        <div class="card-status-section">
          <span class="card-status-label">Status:</span> <span class="card-status">Coming soon...</span>
        </div>
        <div>
          <span class="card-tag">Coming soon...</span>
        </div>
        <div class="card-contact">
          <a href="mailto:ilya.muz@gmail.com">Contact</a>
        </div>
      </div>
    </a>
  </div>
  <!-- Claddagh NicLochlainn -->
  <div class="card">
    <a href="claddagh-project/">
      <div class="card-image">
        <img src="/images/newspeak-logo.png" alt="Claddagh's Project Screenshot" class="project-logo-image">
        <div class="profile-image">
          <img src="/images/Claddagh.jpeg" alt="Claddagh NicLochlainn">
        </div>
      </div>
      <div class="card-content">
        <h3 class="card-title">Claddagh NicLochlainn</h3>
        <p class="card-description">Coming soon...</p>
        <div class="card-section">
          <h4>Problem</h4>
          <p>Coming soon...</p>
        </div>
        <div class="card-section">
          <h4>Solution</h4>
          <p>Coming soon...</p>
        </div>
        <div class="card-status-section">
          <span class="card-status-label">Status:</span> <span class="card-status">Coming soon...</span>
        </div>
        <div>
          <span class="card-tag">Coming soon...</span>
        </div>
        <div class="card-contact">
          <a href="mailto:claddaghniclochlainn@gmail.com">Contact</a>
        </div>
      </div>
    </a>
  </div>
  <!-- David Norton -->
  <div class="card">
    <a href="david-project/">
      <div class="card-image">
        <img src="/images/newspeak-logo.png" alt="David's Project Screenshot" class="project-logo-image">
        <div class="profile-image">
          <img src="/images/David.jpeg" alt="David Norton">
        </div>
      </div>
      <div class="card-content">
        <h3 class="card-title">David Norton</h3>
        <p class="card-description">Coming soon...</p>
        <div class="card-section">
          <h4>Problem</h4>
          <p>Coming soon...</p>
        </div>
        <div class="card-section">
          <h4>Solution</h4>
          <p>Coming soon...</p>
        </div>
        <div class="card-status-section">
          <span class="card-status-label">Status:</span> <span class="card-status">Coming soon...</span>
        </div>
        <div>
          <span class="card-tag">Coming soon...</span>
        </div>
        <div class="card-contact">
          <a href="mailto:david.william.norton@gmail.com">Contact</a>
        </div>
      </div>
    </a>
  </div>
  <!-- Dorcas Nyamwaya -->
  <div class="card">
    <a href="dorcas-project/">
      <div class="card-image">
        <img src="/images/newspeak-logo.png" alt="Dorcas's Project Screenshot" class="project-logo-image">
        <div class="profile-image">
          <img src="/images/Dorcas.jpeg" alt="Dorcas Nyamwaya">
        </div>
      </div>
      <div class="card-content">
        <h3 class="card-title">Dorcas Nyamwaya</h3>
        <p class="card-description">Coming soon...</p>
        <div class="card-section">
          <h4>Problem</h4>
          <p>Coming soon...</p>
        </div>
        <div class="card-section">
          <h4>Solution</h4>
          <p>Coming soon...</p>
        </div>
        <div class="card-status-section">
          <span class="card-status-label">Status:</span> <span class="card-status">Coming soon...</span>
        </div>
        <div>
          <span class="card-tag">Coming soon...</span>
        </div>
        <div class="card-contact">
          <a href="mailto:adongonyamwaya@gmail.com">Contact</a>
        </div>
      </div>
    </a>
  </div>
  <!-- Alex Papadopoulos -->
  <div class="card">
    <a href="alex-project/">
      <div class="card-image">
        <img src="/images/newspeak-logo.png" alt="Alex's Project Screenshot" class="project-logo-image">
        <div class="profile-image">
          <img src="/images/Alex.jpeg" alt="Alex Papadopoulos">
        </div>
      </div>
      <div class="card-content">
        <h3 class="card-title">Alex Papadopoulos</h3>
        <p class="card-description">Coming soon...</p>
        <div class="card-section">
          <h4>Problem</h4>
          <p>Coming soon...</p>
        </div>
        <div class="card-section">
          <h4>Solution</h4>
          <p>Coming soon...</p>
        </div>
        <div class="card-status-section">
          <span class="card-status-label">Status:</span> <span class="card-status">Coming soon...</span>
        </div>
        <div>
          <span class="card-tag">Coming soon...</span>
        </div>
        <div class="card-contact">
          <a href="mailto:me@imalexnow.io">Contact</a>
        </div>
      </div>
    </a>
  </div>
  <!-- Tristan Spill -->
  <div class="card">
    <a href="tristan-project/">
      <div class="card-image">
        <img src="/images/newspeak-logo.png" alt="Tristan's Project Screenshot" class="project-logo-image">
        <div class="profile-image">
          <img src="/images/Tristan.jpeg" alt="Tristan Spill">
        </div>
      </div>
      <div class="card-content">
        <h3 class="card-title">Tristan Spill</h3>
        <p class="card-description">Coming soon...</p>
        <div class="card-section">
          <h4>Problem</h4>
          <p>Coming soon...</p>
        </div>
        <div class="card-section">
          <h4>Solution</h4>
          <p>Coming soon...</p>
        </div>
        <div class="card-status-section">
          <span class="card-status-label">Status:</span> <span class="card-status">Coming soon...</span>
        </div>
        <div>
          <span class="card-tag">Coming soon...</span>
        </div>
        <div class="card-contact">
          <a href="mailto:tspill@gmail.com">Contact</a>
        </div>
      </div>
    </a>
  </div>
  <!-- Melissa Tranfield -->
  <div class="card">
    <a href="melissa-project/">
      <div class="card-image">
        <img src="/images/newspeak-logo.png" alt="Melissa's Project Screenshot" class="project-logo-image">
        <div class="profile-image">
          <img src="/images/Mel.jpeg" alt="Melissa Tranfield">
        </div>
      </div>
      <div class="card-content">
        <h3 class="card-title">Melissa Tranfield</h3>
        <p class="card-description">Coming soon...</p>
        <div class="card-section">
          <h4>Problem</h4>
          <p>Coming soon...</p>
        </div>
        <div class="card-section">
          <h4>Solution</h4>
          <p>Coming soon...</p>
        </div>
        <div class="card-status-section">
          <span class="card-status-label">Status:</span> <span class="card-status">Coming soon...</span>
        </div>
        <div>
          <span class="card-tag">Coming soon...</span>
        </div>
        <div class="card-contact">
          <a href="mailto:mrotranfield@gmail.com">Contact</a>
        </div>
      </div>
    </a>
  </div>
  <!-- Casimir Wanot -->
  <div class="card">
    <a href="casimir-project/">
      <div class="card-image">
        <img src="/images/newspeak-logo.png" alt="Casimir's Project Screenshot" class="project-logo-image">
        <div class="profile-image">
          <img src="/images/Casimir.jpeg" alt="Casimir Wanot">
        </div>
      </div>
      <div class="card-content">
        <h3 class="card-title">Casimir Wanot</h3>
        <p class="card-description">Coming soon...</p>
        <div class="card-section">
          <h4>Problem</h4>
          <p>Coming soon...</p>
        </div>
        <div class="card-section">
          <h4>Solution</h4>
          <p>Coming soon...</p>
        </div>
        <div class="card-status-section">
          <span class="card-status-label">Status:</span> <span class="card-status">Coming soon...</span>
        </div>
        <div>
          <span class="card-tag">Coming soon...</span>
        </div>
        <div class="card-contact">
          <a href="mailto:casimir@mantis.red">Contact</a>
        </div>
      </div>
    </a>
  </div>
  <!-- Simon Wisdom -->
  <div class="card">
    <a href="https://chatlinks.xyz/">
      <div class="card-image">
        <img src="https://chatlinks.xyz/assets/chatlinks-logo.png" alt="Simon's Project Screenshot" class="project-logo-image chatlinks-logo-fix">
        <div class="profile-image">
          <img src="/images/Simon.jpeg" alt="Simon Wisdom">
        </div>
      </div>
      <div class="card-content">
        <h3 class="card-title">Simon Wisdom</h3>
        <p class="card-description">Chatlinks is a tool to extract useful information from Whatsapp Group Chats.</p>
        <div class="card-section">
          <h4>Problem</h4>
          <p>Everyone from community organisers to politicians to small businesses is in too many group chats that contain info that gets buried. Lots of things are missed as a result.</p>
        </div>
        <div class="card-section">
          <h4>Solution</h4>
          <p>Chatlinks extracts things you care about from your group chats. I've started with extracting events, planning to expand to Links, Jobs, News, etc.</p>
        </div>
        <div class="card-status-section">
          <span class="card-status-label">Status:</span> <span class="card-status">Beta version is live at chatlinks.xyz</span>
        </div>
        <div>
          <span class="card-tag">Communication</span>
          <span class="card-tag">Organising</span>
        </div>
        <div class="card-contact">
          <a href="mailto:simonowisdom@gmail.com">Contact</a>
        </div>
      </div>
    </a>
  </div>
  <!-- Yung-Hsuan Wu -->
  <div class="card">
    <a href="yung-hsuan-project/">
      <div class="card-image">
        <img src="/images/newspeak-logo.png" alt="Yung-Hsuan's Project Screenshot" class="project-logo-image">
        <div class="profile-image">
          <img src="/images/Yung-Hsuan.jpeg" alt="Yung-Hsuan Wu">
        </div>
      </div>
      <div class="card-content">
        <h3 class="card-title">Yung-Hsuan Wu</h3>
        <p class="card-description">Coming soon...</p>
        <div class="card-section">
          <h4>Problem</h4>
          <p>Coming soon...</p>
        </div>
        <div class="card-section">
          <h4>Solution</h4>
          <p>Coming soon...</p>
        </div>
        <div class="card-status-section">
          <span class="card-status-label">Status:</span> <span class="card-status">Coming soon...</span>
        </div>
        <div>
          <span class="card-tag">Coming soon...</span>
        </div>
        <div class="card-contact">
          <a href="mailto:yung-hsuan.wu@graduateinstitute.ch">Contact</a>
        </div>
      </div>
    </a>
  </div></h3>
    