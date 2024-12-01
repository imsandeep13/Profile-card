<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Profile Card with Social Media Links</title>
  <link rel="stylesheet" href="styles.css">
  <!-- Font Awesome for Social Media Icons -->
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" rel="stylesheet">
</head>
<body>
  <div class="profile-card">
     <img src="C:\Users\Admin\Downloads\Snapchat-1405221578.jpg" alt="Profile Image" class="profile-img">
    <h2 class="name">Sandeep Kumar</h2>
    <p class="job-title">Backend Developer!!Application Engineer</p>
    <p class="bio">Currently Working As a IT Professional,Previously Experienced with Application Engineer </p>
    
    <!-- Social Media Links -->
    <div class="social-links">
      <a href="https://www.instagram.com/sandeep.shandilya13?igsh=MWJqOTludXd6Y2M3NA=="><i class="fab fa-instagram"></i></a>
      <a <a href="https://www.linkedin.com/in/sandeep-kumar-47a271202?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app"><i class="fab fa-linkedin"></i></a>
      <a href="https://www.facebook.com/imsandeep13?mibextid=ZbWKwL"><i class="fab fa-facebook"></i></a>
    </div>
  </div>
</body>
</html>
/* Reset some default styles */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  background-color: #f4f4f4;
}

.profile-card {
  width: 300px;
  padding: 20px;
  background-color: #fff;
  border-radius: 10px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  text-align: center;
  transition: transform 0.3s ease;
}

.profile-card:hover {
  transform: translateY(-10px);
}

.profile-img {
  width: 100px;
  height: 100px;
  border-radius: 50%;
  object-fit: cover;
  margin-bottom: 15px;
}

.name {
  font-size: 24px;
  font-weight: bold;
  color: #333;
}

.job-title {
  font-size: 18px;
  color: #777;
  margin: 5px 0;
}

.bio {
  font-size: 14px;
  color: #555;
  margin-top: 10px;
  line-height: 1.5;
}

.social-links {
  margin-top: 20px;
}

.social-icon {
  text-decoration: none;
  font-size: 24px;
  margin: 0 10px;
  color: #555;
  transition: color 0.3s ease;
}

.social-icon:hover {
  color: #0077b5; /* LinkedIn Blue (this can be customized for each icon) */
}

.social-icon.instagram:hover {
  color: #e4405f; /* Instagram Pink */
}

.social-icon.linkedin:hover {
  color: #0077b5; /* LinkedIn Blue */
}

.social-icon.facebook:hover {
  color: #1877f2; /* Facebook Blue */
}
