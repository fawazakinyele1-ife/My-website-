# My-website-
A repository about my personal details "about me"
document.getElementById('about-me').innerText = 'Hello, I am Akinyele Fawaz. I am a Student. A boy, 3 feet tall dark in complexion, blood group A, having severe headaches during rainy season and so on';

const projects = [
  { name: 'X-city', url: 'http:                    
];

const projectList = document.getElementById('//www.X-city.com' },
];

const projectList = document.getElementById('project-list');
projects.forEach(project => {
  const li = document.createElement('li');
  const a = document.createElement('a');
  a.href = project.url;
  a.innerText = project.name;
  li.appendChild(a);
  projectList.appendChild(li);
});
