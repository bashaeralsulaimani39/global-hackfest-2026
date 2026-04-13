   # Submission guide

   Step-by-step: what to have ready and where to put it.

   ## What you need

   | Item | Notes |
   |------|--------|
   | GitHub repo | Public, with code and docs |
   | Demo video | Max 5 min, shows the project working |
   | Project logo | 1:1, min 500×500, PNG/JPG (optional) |
   | Live demo URL | If you have one |
   | Project docs | README + go-to-market plan (required). Use the project template. |
   | Participant intro video | 30–60 sec, required; used at Hong Kong conference |
   | Pitch deck | Optional; PDF or slides link |

   ## Repo contents

   **Required:** README (from template), LICENSE (MIT/Apache 2.0/etc.), dependency file, and how to run/deploy. Include source, contracts (on Conflux testnet or mainnet), frontend/backend if you have them, and tests.

   **Docs:** Describe the project and goals. Go-to-market plan is required (how you’ll launch and grow it). Add architecture, setup steps, usage, how you use Conflux, and any Privy/Pyth/LayerZero usage.

   ### 3. Deploy Your Project

   #### Conflux Network Deployment
   Your project must be deployed to one of:
   - **Conflux Core Space** (mainnet or testnet)
   - **Conflux eSpace** (mainnet or testnet)
   - **Cross-Space** integration

   #### Deployment Verification
   - Provide contract addresses and transaction hashes
   - Include network configuration details
   - Ensure all functionality is accessible
   - Test all user flows and integrations

   ### 4. Add to Projects Folder

   #### Fork and Clone Repository
   1. **Fork the repository**: [global-hackfest-2026](https://github.com/conflux-fans/global-hackfest-2026)
   2. **Clone your fork**: `git clone https://github.com/your-username/global-hackfest-2026`
   3. **Navigate to projects folder**: `cd global-hackfest-2026/projects/`

   #### Create Your Project Folder
   1. **Create project folder**: Use kebab-case naming (e.g., `my-awesome-project`)
   2. **Add project files**:
      ```
      projects/my-awesome-project/
      ├── README.md              # Project documentation
      ├── demo/                  # Demo materials folder
      │   ├── demo-video.mp4     # Demo video file
      │   └── screenshots/       # UI screenshots
      │       ├── homepage.png
      │       └── features.png
      ├── presentation.pdf       # Pitch deck (optional)
      └── links.md              # External links (repo, demo, etc.)
      ```

   #### Submit Pull Request
   1. **Commit your changes**: `git add . && git commit -m "Add [project-name] to hackathon"`
   2. **Push to your fork**: `git push origin main`
   3. **Create pull request**: Submit PR to the main repository
   4. **Wait for review**: Organizers will review and merge your submission

   ### 5. Submit to Electric Capital Open Dev Data

   To ensure your project is counted in the Conflux ecosystem developer report, you must create a pull request to the Electric Capital Open Dev Data repository.

   #### Steps to Create the PR:

   1. **Fork the repository**: [electric-capital/open-dev-data](https://github.com/electric-capital/open-dev-data)
   2. **Create a migration file**: 
      - Navigate to the `migrations/` folder
      - Create a new file with format: `YYYY-MM-DDThhmmss_your_project_name`
      - Example: `2026-05-01T120000_my_awesome_project`
   3. **Add the migration content**:
      ```
      repadd Conflux https://github.com/your-username/your-project-repo
      ```
      Optionally add tags:
      ```
      repadd Conflux https://github.com/your-username/your-project-repo #protocol
      ```
   4. **Submit the pull request** with a clear description
   5. **Reference example PR**: See [PR #2475](https://github.com/electric-capital/open-dev-data/pull/2475) for format reference

   **Note**: The PR does not need to be merged before submission deadline, but it must be created and submitted.

   ### 6. Post Social Media Announcement

   Create a tweet on Twitter/X announcing your project submission:

   1. **Post on Twitter/X** with your project announcement
   2. **Tag required accounts**: 
      - @ConfluxDevs
      - @ConfluxNetwork
   3. **Include relevant hashtags**: #ConfluxHackathon #globalhackfest26
   4. **Share project highlights**: Brief description, demo link, and what makes it unique
   5. **Include link to your project**: GitHub repository or live demo URL

   **Example tweet format**:
   ```
   🚀 Excited to submit [Project Name] for Global Hackfest 2026! 

   [Brief description]

   🔗 [Demo/Repo Link]

   @ConfluxDevs @ConfluxNetwork #globalhackfest26
   ```

   ### 8. Submit Grant Proposal (Optional - Bonus Points)

   To encourage long-term building, you can earn bonus points during judging by submitting a grant proposal.

   1.  **Visit the Conflux Forum**: [Grant Proposals Section](https://forum.conflux.fun/c/English/grant-proposals)
   2.  **Use the application template**: Follow the [Integration Grants Application Template](https://forum.conflux.fun/t/integration-grants-application-template/20759) when drafting your proposal.
   3.  **Draft your proposal**: Outline your project's future roadmap, budget requirements, and value to the ecosystem.
   4.  **Post the proposal**: Submit it to the forum.
   5.  **Include the link**: Add the link to your forum post in your submission PR.

   ### 9. Create Submission PR

   1. **Go to the hackathon repository**: [global-hackfest-2026](https://github.com/conflux-fans/global-hackfest-2026)
   2. **Open a Submission Pull Request** from your fork with your `/projects/` folder changes
   3. **Use the submission template** and fill out all required fields completely and accurately, including:
      - Link to your Electric Capital PR
      - Link to your social media post
   4. **Submit the Pull Request** before the deadline (2026-04-20 @ 11:59:59)

   #### Submission Template Fields

   ```markdown
   ## Project Information
   - **Project Name**: [Your project name]
   - **Hackathon**: Global Hackfest 2026
   - **Team Members**: [List all team members with GitHub usernames - up to 5]
   - **Project Description**: [Brief 2-3 sentence description]

   ## Links and Resources
   - **GitHub Repository**: [Public repository URL]
   - **Projects Folder**: [Link to your folder in /projects/]
   - **Live Demo**: [Deployed application URL]
   - **Demo Video**: [YouTube/Vimeo link or file in projects folder]
   - **Grant Proposal**: [Link to Conflux Forum post - Optional]
   - **Pitch Deck**: [Google Slides or PDF link]
   - **Project Website**: [If applicable]

   ## Technical Details
   - **Conflux Network**: [Core Space / eSpace / Cross-Space]
   - **Contract Addresses**: [List deployed contract addresses]
   - **Partner Integrations**: [Privy / Pyth / LayerZero usage]
   - **Tech Stack**: [Languages, frameworks, tools used]

   ## Innovation Areas
   Which areas does your project focus on? (Check all that apply)
   - [ ] AI + Blockchain Integration
   - [ ] Developer Experience & Tooling
   - [ ] DeFi Innovation
   - [ ] Real-World Applications
   - [ ] Other: [Specify]

   ## Submission Checklist
   - [ ] Project deployed to Conflux network
   - [ ] GitHub repository is public and complete
   - [ ] Added to /projects/ folder with PR submitted
   - [ ] README follows provided template (includes go-to-market plan)
   - [ ] Demo video uploaded (max 5 minutes)
   - [ ] All team members listed (up to 5)
   - [ ] Code includes proper documentation
   - [ ] License file included
   - [ ] Project integrates meaningfully with Conflux
   - [ ] Electric Capital PR created to add project to Conflux ecosystem
   - [ ] Social media post published tagging @ConfluxDevs and @ConfluxNetwork
   ```

   ### 6. Create Your Demo Video

   #### Video Requirements
   - **Duration**: 3-5 minutes maximum
   - **Format**: MP4, MOV, or YouTube/Vimeo link
   - **Quality**: Minimum 720p resolution
   - **Audio**: Clear narration explaining the project

   #### Content Structure
   1. **Introduction** (30 seconds)
      - Team introduction
      - Project name and hackathon
      - Problem statement

   2. **Solution Overview** (60 seconds)
      - High-level solution explanation
      - Key features and benefits
      - Conflux integration highlights

   3. **Live Demo** (2-3 minutes)
      - User journey walkthrough
      - Key features demonstration
      - Technical highlights

   4. **Technical Implementation** (60 seconds)
      - Architecture overview
      - Conflux features used
      - Challenges overcome

   5. **Conclusion** (30 seconds)
      - Impact and future plans
      - Call to action

   ### 7. Create Your Participant Intro Video (required)

   Every submission must include a participant intro video. This is separate from the demo video and from the winner video (which only winners submit after the announcement).

   #### Video requirements
   - **Duration:** 30–60 seconds total
   - **Language:** Your native language or English
   - **Format:** 16:9 landscape
   - **Framing:** Front facing, clean audio, simple background

   #### Content
   Say who you are, what you're building for Global Hackfest 2026, and that you're excited to participate. Example: "I'm [Name] from [Country/City], building [Project Name] for Conflux Network's Global Hackfest 2026 and I'm excited to participate."

   These clips will be used in a conference showcase in Hong Kong. Submissions missing required items (including this video) may be treated as incomplete and not eligible for prizes.

   ## 📋 Submission Checklist

   ### Before Submitting
   - [ ] Project is fully functional and deployed
   - [ ] All code is committed to public GitHub repository
   - [ ] Added project to appropriate /projects/ folder
   - [ ] README.md follows the provided template
   - [ ] Demo video is complete and under 5 minutes
   - [ ] Participant intro video (30–60 sec) submitted
   - [ ] All team members are listed in submission
   - [ ] Project integrates with Conflux network
   - [ ] Partner technologies are properly implemented
   - [ ] License file is included in repository
   - [ ] Documentation is comprehensive and clear

   Missing any required item may result in your project being ineligible for prizes.

   ### Technical Requirements
   - [ ] Smart contracts deployed to Conflux testnet or mainnet
   - [ ] Frontend application is accessible via provided URL
   - [ ] All dependencies are properly documented
   - [ ] Setup instructions are clear and complete
   - [ ] Project demonstrates meaningful Conflux integration
   - [ ] Code follows best practices and is well-commented

   ### Submission Materials
   - [ ] GitHub repository URL provided
   - [ ] Project added to /projects/ folder
   - [ ] Demo video uploaded and accessible
   - [ ] Participant intro video uploaded and accessible
   - [ ] Live demo URL is functional
   - [ ] Project logo meets size requirements
   - [ ] Pitch deck uploaded (if applicable)
   - [ ] Electric Capital PR created and link provided
   - [ ] Social media post published and link provided
   - [ ] All required fields in submission template completed

   ## ❓ Frequently Asked Questions

   ### General Submission Questions

   **Q: Should each team member submit individually, or should one person submit for the entire team?**
   A: One team member (preferably the team lead) should submit for the entire team. Make sure all team members are listed in the submission.

   **Q: Can I keep my GitHub repository private?**
   A: No, all repositories must be public for judging. If you have concerns about intellectual property, consider using an appropriate open source license.

   ### Technical Questions

   **Q: Do we need to deploy to Conflux mainnet?**
   A: Projects can be deployed to either Conflux testnet or mainnet. Testnet deployment is acceptable for judging.

   **Q: What if our project uses multiple Conflux spaces?**
   A: Cross-space projects are encouraged! Clearly document your architecture and provide deployment details for all spaces used.

   **Q: Can we use external APIs and services?**
   A: Yes, but your project must have meaningful integration with the Conflux network. External services should enhance, not replace, Conflux functionality.

   **Q: What programming languages are allowed?**
   A: Any language is acceptable, but projects must integrate with Conflux. Popular choices include Solidity for smart contracts and JavaScript/TypeScript for frontends.

   ### Submission Process Questions

   **Q: Can I edit my submission after submitting?**
   A: Yes, you can edit your submission PR until the deadline. However, your repository should reflect the final state of your project.

   **Q: What if I miss the submission deadline?**
   A: Late submissions will not be accepted. Ensure you submit well before the deadline to account for any technical issues.

   **Q: Can I continue working on my project after submission?**
   A: Yes! We encourage continued development. However, only work completed before the submission deadline will be considered for judging.

   ### Judging and Evaluation

   **Q: What are the judging criteria?**
   A: Projects are evaluated on technical implementation, Conflux integration, innovation, user experience, and presentation quality. See our judging criteria doc for details.

   **Q: When will winners be announced?**
   A: Winners will be announced on April 27, 2026, after the 1-week judging period (starting April 21, 2026). All participants will be notified via Discord and social media.

   **Q: What if a team member drops out before submission?**
   A: Update your submission to reflect the current team composition. Ensure the remaining team members can complete and present the project.

   ## 🆘 Getting Help

   ### Technical Support
   - **Discord**: https://discord.gg/4A2q3xJKjC - Real-time help and support
   - **GitHub Discussions**: Post detailed technical questions
   - **Office Hours**: Weekly live sessions with Conflux engineers
   - **Mentor Program**: Schedule 1-on-1 sessions with mentors

   ### Submission Support
   - **Discord**: https://discord.gg/4A2q3xJKjC
   - **Telegram**: https://t.me/ConfluxDevs
   - **Documentation**: https://doc.confluxnetwork.org/

   ---

   **Need help with your submission? Don't hesitate to reach out to our team through Discord or Telegram. We're here to ensure every team can successfully submit their project!**
