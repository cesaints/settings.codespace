# Project Setup and Configuration

## 1. Docker and WSL Installation
- Installed **Docker** on Windows.  
- Enabled **WSL (Windows Subsystem for Linux)** and installed **Ubuntu**.  
- Installed **Docker Engine** inside Ubuntu.  
- Added Docker’s official **GPG key**.  
- Added the Docker repository to the **APT package sources**.  
- Granted permissions for the current user to run Docker without `sudo`.  

## 2. Node.js Environment
- Installed **NVM (Node Version Manager)** to handle Node.js versions.  
- Selected the **LTS (Hydrogen)** release for stability and long-term support.  
- Created an **.nvmrc** file with the correct Node.js version.  

## 3. Git and GitHub Setup
- Configured **Git** locally.  
- Connected **GitHub** via SSH:  
  1. Generated a new SSH key.  
  2. Added the key to the SSH agent.  
  3. Registered the SSH key on GitHub.  

## 4. Project Dependencies
- Installed and configured:  
  - **Next.js** `13.1.6`  
  - **React** `18.2.0`  
  - **React-DOM** `18.2.0`  

## 5. Development Environment
- Configured the project to run with:  

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
