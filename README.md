# Customizing your organization's profile

## About your organization's profile page
You can customize your organization's Overview page to show a README and pinned repositories dedicated to public users or members of the organization.

Members of your organization who are signed into GitHub, can select a member or public view of the README and pinned repositories when they visit your organization's profile page.

The view defaults to member if either a members-only README or members-only pinned repositories are present, and public otherwise.

Users who are not members of your organization will be shown a public view.

### Pinned repositories

You can give users easy access to important or frequently used repositories, by choosing up to six repositories for public users and six repositories for members of the organization. Once you pin repositories to your organization profile, the "Pinned" section is shown above the "Repositories" section of the profile page.

Only organization owners can pin repositories. For more information, see "Pinning repositories to your organization's profile."

### Organization profile READMEs
You can share information about how to engage with your organization by creating an organization profile README for both public users and members of the organization. GitHub shows your organization profile README in the "Overview" tab of your organization.

You can choose what information to include in your organization profile README. Here are some examples of information that may be helpful.

	An "About" section that describes your organization
	Guidance for getting help in the organization

You can format text and include emoji, images, and GIFs in your organization profile README by using GitHub Flavored Markdown. For more information, see "Getting started with writing and formatting on GitHub."

## Adding a public organization profile README

The content of public README.md will appear on your organization's public profile.

1. If your organization does not already have a public .github repository, create a public .github repository.
2. In your organization's .github repository, create a README.md file in the profile folder.
3. Commit the changes to the README.md file.

## Adding a member-only organization profile README

The content of a member-only README.md will be displayed in the member view of your organization's profile.

1. If your organization does not already have a .github-private repository, create a private repository called .github-private.
2. In your organization's .github-private repository, create a README.md file in the profile folder.
3. Commit the changes to the README.md file.
## Pinning repositories to your organization's profile

You can pin repositories that you want to feature, such as those that are frequently used, to your organization's profile page. To choose which repositories to pin to your organization's profile, you must be an organization owner.

1. Navigate to your organization's profile page.

2. In the right sidebar of the page, select the  View as dropdown menu, then click Public or Member.

3. Navigate to the settings for pinned repositories.

		If you already have pinned repositories, in the "Pinned" section, click Customize pins.

		If you haven't yet pinned any repositories, in the right sidebar, click pin repositories.

4. In the "Edit pinned repositories" dialog box, select a combination of up to six public, or private repositories to display.

5. Click Save pins.
