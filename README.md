 Hi there 👋

<!-- =========================
     👋 ReactJS Code-Style Intro
========================= -->
```jsx
import React from "react";

const DeveloperProfile = () => {
  const name = "Akerele Olamide";
  const role = "Full-Stack Developer";
  const skills = ["HTML", "CSS", "JavaScript", "React", "Node.js"];
  const interests = ["Open Source", "AI", "Web Development"];

  const greet = () => "Welcome to my GitHub profile!";

  return (
    <div>
      <h1>Hello World 👋</h1>
      <h2>{`I'm Akerele Olamide - Web-developer`}</h2>
      <p>{greet()}</p>
      <p>Skills: {skills.join("Soft-skills, web-design, Virtual Assistant")}</p>
      <p>Interests: {interests.join("AI, Web-3, Application design")}</p>
    </div>
  );
};

export default DeveloperProfile;.
-->
