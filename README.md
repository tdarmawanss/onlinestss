# onlinestss


##### Set up GIT
https://docs.github.com/en/get-started/getting-started-with-git/set-up-git#password-caching

##### Set up SSH connection with git remote repo
https://code.tutsplus.com/quick-tip-how-to-work-with-github-and-multiple-accounts--net-22574t


# Local WordPress Development Setup Guide (Using Local by WP Engine)

## Prerequisites
- Download and install **Local**: [https://localwp.com](https://localwp.com)

## Steps to Set Up

### 1. Create a New WordPress Site
- Open **Local**
- Click **“+ New Site”**
- Enter site name (e.g., `my-local-site`)
- Choose environment (Preferred is fine for most)
- Set WordPress username, password, email
- Click **“Add Site”**

### 2. Access Your Site
- **Admin Dashboard**: Click **“WP Admin”**
- **Frontend URL**: Click **“Open Site”**
- **Database**: Click **“Database”** tab → Open **Adminer**

### 3. Add Plugins/Themes
- Drag and drop plugin/theme zip files into `/app/public/wp-content/plugins` or `/themes`
- Activate from WP Admin

## Tips
- Enable **Live Links** to share your local site temporarily
- Use **WP-CLI** from the site’s **SSH terminal** (right-click → “Open Site Shell”)
