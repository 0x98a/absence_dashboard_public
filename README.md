
# (!) UNRELEASED (!)
This project is still unreleased, until i upload the files in the coming week or days.
I am currently cleaning the sourecode of the project so its not a mess and be used/continued by other people.

Hence im the only one working on this (as you can read in the about me) this may take some time

&nbsp;

# absence.gg dashboard
## about (why this is getting released)
This is the sourcecode of the absence.gg dashboard, getting released due to a conflict that happen between me and the other owner, where he got mad that i didnt finish the registration page in time (in like a week) cause i didnt feel like, this is after i paid his friend 650€, paid for all the software we use (themida, around 300€) and a GUI that i also paid for 100€, while keeping the server up for over 1.5 years (around 350€) and multiples times paid him in crypto cause he couldnt afford anything.
This is also after him saying i have the audacity to talk when i can finish registration etc when i have made around 750+ commits on the authentication api & website alone, while he did 11 commits on the project itself.

I really dont feel like continuing this project due to all the money ive put into this and not gotten a single thing out of it, even my old partner tried to destroy new plans when i "replaced" him.

This should be used as a platform to see how we did stuff with authentication, and other stuff and should not be expected to be able to copy & paste and run this stuff.

I will upload both the API and the website source in this, both the render and the serverside that was parsing the data.

&nbsp;

## Prerequisites
Make sure you have the following installed:
- Node.js (v10.7.0 or higher)
- npm (comes with Node.js)

&nbsp;
## Installation
### Clone the repository:
```
git clone https://github.com/0x98a/absence_dashboard_public.git
cd absence_dashboard_public
```

### Install dependencies:
```
npm i
```

After this remember to edit the .ENV file to configure the database connection and etc, a version with support for 0 users will soon be uploaded so this can be used publicly.

SQL files will soon be provided.

&nbsp;
## Running the Project
Once the packages are installed, you can start the development server:
```
npm run dev
```
The application should now be running at http://localhost:3000.

&nbsp;

## Project Structure
Here’s an overview of the essential files and folders:
```
/components         # Reusable UI components
/pages              # Next.js page components
/lib                # Helper functions and service calls
```

&nbsp;
## Scripts
- `npm run dev`: Starts the development server.
- `npm run build`: Builds the project for production.
- `npm start`: Runs the production server.
- `npm run lint`: Lints the project for code quality.
