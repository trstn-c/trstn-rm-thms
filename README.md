# trstn-rm-thms
- 👋 Hello there, I'm Trstn. I'm a maker currently studying at AUA for a BFA.
- 📅 I've been using Roam for a bit more than a month and somewhere in week two or so I started playing around with themes others had made and then decided to make my own.
- 🔨 This is a repo for my roam theming work and experimentation.
  - I only know CSS from playing around making quick websites on and off through the years.
  - Bit out of my depths but intently trying to figure things out.  

- 💬 Any critique or suggestions or help with any aspect of a theme that I'm struggling with is appreciated. I can be easily found at @trstn_ca
  
## Themes
- Currently I have a few themes in progress and a bunch more planned
- For now, the only one ready for use is el-n
### Global Goals
- Follow the KISS principle where possible
- Aim for DRYness (this isn't always easy to do, sometimes especially so when the things you're working with aren't that DRY in the first place)
- Functionality first
- Stay faithful to the general design architecture
  - I intend to augment and amplify the interface that already exists. 
  - I don't have any interest in creating an alternative interface, and those who do, do it better than I would.
# el-n
Install with @import url('https://raw.githubusercontent.com/trstn-c/trstn-rm-thms/main/el-n/el-n.css'); or by copying the CSS found in el-n to your roam/css
## Blurb
- Inspired by a playful mix of form, function & fun; and my ex and some of the conversations we had in the past.
- Soft shadows for soft vibes
- Uses SF Compact for the sidebar and SF Pro for main content, if San Francisco isn't installed, it'll use Overpass
- Primary, secondary, and tertiary accents dictate internal, external, and tag links as well as the colours of a few parts of the interface
- Block reference underline is translucent, and block references pop out slightly on hover
- Custom tags aren't included by default but can be implemented by adding the CSS found at the bottom of this page to the end of the theme or making another section on your roam/css page and inputting it there.
### Roadmap
- All pages page
- Better buttons
- Polishing of alignments
## Preview
![](/Images/el-n_mainPreview.png)
### References
![](/Images/el-n_references.png)
### Kanban
![](/Images/el-n_kanban.png)
## Tag Styling
```
/* an emoji or other thing before "yourTag" */
span.rm-page-ref[data-tag=yourTag]::before {
  content: "💭 ";
}

/* inbox */
span.rm-page-ref[data-tag=Inbox] {
  background: #FFD800 !important !important;
  color: #16161D !important;
  border-radius: 4px;
  padding: 4px 6px;
}

/* urgent */
span.rm-page-ref[data-tag=Urgent] {
  background: #F21D37 !important;
  color: var(--sidebar-background) !important;
  border-radius: 4px;
}

/* twitter */
span.rm-page-ref[data-tag=Twitter] {
  background: #1da1f2 !important;
  color: var(--sidebar-background) !important;
  border-radius: 4px;
  padding: 4px 6px;
}

/* coffee */
span.rm-page-ref[data-tag=Coffee] {
  color: #483526 !important;
}
```
