# BubbleCV Template

This is a professional CV template inspired by the legendary secret agent James Bond.
BubbleCV is designed to effectively showcase your skills, work experience, education, and contact information in a sleek and impactful manner.


## Key Features

- `\begin{cv}[<avatar>][<avatar_size>][<avatar_color>]{<name>}{<description>}`: Creates the main CV environment with optional parameters for avatar image, size, and color. It also includes the name and description of the individual.

- `\cvsection[<icon>][<icon_size>][<icon_color>]{<section_title>}`: Creates a new section with an optional icon, size, and color parameters. It helps in organizing different parts of the CV, such as Profile, Work Experience, Education, etc.

- `\begin{cvevent}[<start_year>][<end_year>]`: Begins a new work experience or educational event. Optional start and end years can be specified to indicate the duration of the event.

- `\cvname{<name>}`: Displays the name of the individual in the CV.

- `\cvdescription{<description>}`: Provides a brief description of the work experience or educational event.

- `\cvsidebar`: Changes the column from the main section to the sidebar.

- `\cvitem[<fa_icon>][<fa_icon_size>]`: Creates an item in the CV sidebar with an optional icon and size parameter. The full list of FontAwesome icons is available at [this link](https://mirrors.ibiblio.org/CTAN/fonts/fontawesome/doc/fontawesome.pdf).

- `\cvskill{<skill>}{<level_name>}{<level_value>}`: Displays a skill and its corresponding proficiency level.

- `\cvseparator[<spacing>]`: Inserts a 1mm vertical space. An optional parameter can be provided to specify the number of repetitions, allowing you to adjust the spacing as needed.


## License

This CV template is provided under the [Creative Commons CC BY 4.0](LICENSE) license. You are free to use, modify, and distribute the template for personal or professional purposes, as long as you acknowledge the original source.

