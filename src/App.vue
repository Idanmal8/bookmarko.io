<script setup>
import PolicyPage from './components/Policies.vue'
</script>

<template>
  <main class="centered-page">
    <PolicyPage>
      <template #body>
        <p><strong>Effective Date:</strong> 01/05/2025</p>
        <p>Thank you for using Bookmarko. Your privacy is important to us. This Privacy Policy explains how we collect, use, and protect your personal information.</p>

        <h4>1. Introduction</h4>
        <p>
          Bookmarko is a mobile app designed to help users track their reading progress, save favorite books, and achieve reading goals. We are committed to protecting your privacy and ensuring transparency about how your information is handled.
        </p>

        <h4>2. Information We Collect</h4>
        <p><strong>a. Personal Information</strong></p>
        <ul>
          <li>Email address</li>
          <li>Password</li>
        </ul>
        <p>This information is collected through Google Firebase Authentication and securely stored in our database.</p>

        <p><strong>b. App Usage Data</strong></p>
        <p>We do not collect additional personal information such as name, age, or location. However, we store app-specific data related to your reading experience:</p>
        <ul>
          <li>Book progress and bookmarks</li>
          <li>Favorite books</li>
          <li>Achievement tracking (missions completed)</li>
          <li>Settings preferences (animations, themes)</li>
        </ul>
        <p>This data is tied to your account and stored securely.</p>

        <p><strong>Third-Party Data:</strong> We use the Google Books API to allow users to search for book information. No personal data is sent to Google during this process.</p>

        <h4>3. How We Use Your Data</h4>
        <p>We use the data collected solely to:</p>
        <ul>
          <li>Authenticate your login and manage your account</li>
          <li>Store and display your reading progress and app preferences</li>
          <li>Provide functionality like favorites, achievements, and settings</li>
        </ul>
        <p>We do not sell, rent, or share your personal information with third parties for marketing or commercial purposes.</p>

        <h4>4. Third-Party Services</h4>
        <p>We rely on the following third-party services:</p>
        <ul>
          <li>Google Firebase Authentication for user login and security</li>
          <li>Google Books API for retrieving book information</li>
        </ul>
        <p>Please review their privacy policies:<br />
        <a href="https://firebase.google.com/support/privacy" target="_blank">Firebase Privacy Policy</a><br />
        <a href="https://policies.google.com/privacy" target="_blank">Google Privacy Policy</a></p>

        <h4>5. Data Retention</h4>
        <p>We retain your personal data as long as your account is active. You can request account deletion at any time by contacting us at <a href="mailto:BookmarkoHome@gmail.com">BookmarkoHome@gmail.com</a>. Upon deletion, all associated data will be permanently removed from our servers.</p>

        <h4>6. Your Rights</h4>
        <p>As a user, you have the right to:</p>
        <ul>
          <li>Access the data we store about you</li>
          <li>Request correction or deletion of your data</li>
          <li>Withdraw consent at any time</li>
        </ul>
        <p>To exercise these rights, contact us at <a href="mailto:BookmarkoHome@gmail.com">BookmarkoHome@gmail.com</a>.</p>

        <h4>7. Security Measures</h4>
        <p>We take data security seriously and implement the following protections:</p>
        <ul>
          <li>Passwords are securely managed through Firebase</li>
          <li>All sensitive information is encrypted and stored securely in our database</li>
        </ul>

        <h4>8. Children's Privacy</h4>
        <p>Bookmarko is not intended for use by children under the age of 13. We do not knowingly collect data from children.</p>

        <h4>9. Changes to This Policy</h4>
        <p>We may update this Privacy Policy from time to time. Users will be notified of any significant changes via in-app notification or email.</p>

        <h4>10. Contact Us</h4>
        <p>If you have any questions or concerns about this policy, please contact us at: <br />
        Email: <a href="mailto:BookmarkoHome@gmail.com">BookmarkoHome@gmail.com</a></p>

        <p><strong>By using Bookmarko, you agree to this Privacy Policy.</strong></p>
      </template>
    </PolicyPage>
  </main>
</template>

<style scoped>
main {
  margin: 0;
  padding: 0;
  overflow-x: hidden;
  width: 100%;
}

.centered-page {
  width: 100%;
  min-height: 100vh;
  background-color: #eaab50;
  display:flex;
  justify-content: center;
  align-items: center;
  padding: 3rem 0;
  box-sizing: border-box;
  overflow-x: hidden;
}
</style>
