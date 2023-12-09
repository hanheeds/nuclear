# Interactive Visualization of Nuclear Explosion Data

By Hanhee Yang

### Course
- CS 333, Professor Hullman, 12/5/2023

![Alt text](https://github.com/hanheeds/nuclear/blob/main/cs333_a3.png)

### Background
This project focuses on an interactive visualization of nuclear explosion data throughout the history of nuclear weapons. The dataset includes tests and combat uses by the U.S., USSR (Russia), China, France, India, the U.K., and Pakistan. The project is timely due to recent global concerns around nuclear warfare and increased public interest in the history of nuclear weapons.

## Dataset
The dataset was sourced from CORGIS, featuring extensive data on nuclear explosions, including countries involved, test locations, and various attributes of each detonation.

## Project Goals
The primary goal is to provide insightful visualizations that shed light on:
- The history and effects of nuclear weapons.
- Trends in nuclear testing, including the impact of international treaties.
- Geopolitical aspects and numerical data associated with nuclear weapons.

### Visualization Concept
The final concept involves:
- A base map visualization with filters (country, method of deployment, purpose of detonation).
- Interactive elements for selecting specific detonations and viewing detailed information.
- Scatter plot visualizations to depict numerical trends.

### Implementation
- Data cleaning and enrichment, including calculation of blast radius.
- Development of a non-interactive map with geojson, marking explosion locations.
- Implementation of interactive elements (sliders, dropdowns, selection of detonations).
- Development of star plots for detailed visualization of each detonation.
- Integration of a scatter plot for quantitative trend analysis.

## Usage

### Setting Up Local Server

1. **Clone the Repository**
   ```bash
   git clone [repository-link]
   ```
2. **Navigate to the Project Directory**
   ```bash
   cd [project-directory]
   ```
3. **Install Dependencies**
   ```bash
   npm install
   ```
4. **Start the Server**
   ```bash
   npm start
   ```
5. **Access the Application**
   - Open a web browser and navigate to 'localhost:[port-number]'
  

   


