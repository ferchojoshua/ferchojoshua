
import Developer from 'ferchojoshua';
import { Languages, Frameworks } from 'ferchojoshua/skill';

class Biography extends Developer {
  name = 'Gerold Ferchojoshua';
  title = 'Developer';
  location = 'Nicaragua, Leon';
}

class Skill extends Developer {
  languages = ['PHP', 'JavaScript', 'TypeScript', 'C#', 'HTML', ...Languages];
  databases = ['MySQL', 'SQLServer', 'PostgreSQL', 'OracleSQL', 'Sybase'];
  frameworks = ['Laravel', 'Vue', 'React.js', ...Frameworks];
}

export { Biography, Skill };



           
<!---
ferchojoshua/ferchojoshua is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
