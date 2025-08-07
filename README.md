# IndustryResume
# IndustryResume

**IndustryResume** is a specialized tool designed to help STEM PhDs and postdocs successfully transition from academia to industry by transforming their academic CVs into compelling, industry-ready resumes.

## Project Description

This landing page serves as the marketing website for IndustryResume, a product that bridges the gap between academic achievements and industry expectations. The tool helps academic professionals translate their research experience, publications, and specialized skills into language that resonates with industry recruiters and hiring managers.

### Key Features Highlighted:
- 🧠 **AI-Powered Resume Rewriting** - Intelligent transformation of academic content
- 📄 **STEM-Specific Resume Templates** - Industry-optimized formats for different sectors
- 🎯 **Job-Targeted Customization** - Resume optimization for specific opportunities

## File Structure

```
/
├── index.html          # Main landing page
├── style.css           # Responsive CSS styles
└── README.md          # Project documentation
```

## Deployment via GitHub Pages

To deploy this landing page using GitHub Pages:

1. **Enable GitHub Pages:**
   - Go to your repository settings
   - Scroll down to the "Pages" section
   - Under "Source", select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click "Save"

2. **Access Your Site:**
   - Your site will be available at: `https://[username].github.io/[repository-name]`
   - It may take a few minutes for the site to become available

3. **Custom Domain (Optional):**
   - Add a `CNAME` file with your custom domain
   - Configure DNS settings with your domain provider

## Customizing Email Collection with Formspree

The landing page includes an email signup form that's currently configured with a placeholder Formspree endpoint. To activate email collection:

### Step 1: Create a Formspree Account
1. Visit [formspree.io](https://formspree.io)
2. Sign up for a free account
3. Create a new form project

### Step 2: Update the Form Action
1. Copy your unique Formspree form endpoint (e.g., `https://formspree.io/f/abcd1234`)
2. In `index.html`, find this line:
   ```html
   <form class="signup-form" action="https://formspree.io/f/your-form-id" method="POST">
   ```
3. Replace `your-form-id` with your actual Formspree form ID

### Step 3: Configure Form Settings (Optional)
In your Formspree dashboard, you can:
- Set up email notifications
- Configure auto-responses
- Add spam protection
- Export collected emails
- Set up integrations with other tools

### Form Features
- **Email Validation:** Built-in HTML5 email validation
- **Hidden Subject:** Automatically adds "IndustryResume Waitlist Signup" as the email subject
- **Privacy Note:** Clearly states the email usage policy
- **Responsive Design:** Works seamlessly on all devices

## Customization Options

### Colors and Branding
The CSS file uses CSS custom properties for easy color customization. Main brand colors:
- Primary gradient: `#667eea` to `#764ba2`
- Accent color: `#ff6b6b`
- Text color: `#2c3e50`

### Content Updates
- Update hero headlines in the `hero` section
- Modify feature descriptions in the `features` section  
- Customize the problem/solution narrative
- Update footer links and contact information

### Responsive Design
The site is fully responsive with breakpoints at:
- Desktop: 1200px+
- Tablet: 768px - 1199px
- Mobile: 480px - 767px
- Small Mobile: < 480px

## Technical Details

- **Framework:** Vanilla HTML/CSS (no dependencies)
- **Styling:** Modern CSS with Flexbox and Grid
- **Font:** System fonts for optimal loading speed
- **Icons:** Unicode emojis for broad compatibility
- **Form Handling:** Formspree integration
- **Hosting:** Optimized for GitHub Pages

## License

This project is open source and available under the [MIT License](LICENSE).

---

**Questions or Issues?**
Feel free to open an issue in this repository or contact the development team.
