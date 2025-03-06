# OET Website and Handbook Team Data

This repository is designed to contain all team data for the OET website and handbook. New team members can easily be added here.


## Python package dependencies

```
- pre-commit
- pillow
```

## Updating Instructions

1. **Add New Team Member**:
    - Modify the `team.json` file with your name, designation, and description.
    - Execute the `pre-commit run --all` command to make sure that the new section follows the necessary json format

2. **Upload Image**:
    - Upload an image of yourself to the `/people` directory.
    - Use the `crop-image-center.py` script located in the root directory to format your image for the website:
    ```bash
    python crop-image-center.py people/your_image.jpg
    ```
    - Use the newly cropped image in the link for your profile.

## Example

Here is an example of how to add a new team member:

```json
{
    "country": "Germany",
    "description": "A highly skilled engineer with expertise in various programming languages.",
    "designation": "Visionary and Head of Wellbeing",
    "github_link": "",   
    "image_link": "https://raw.githubusercontent.com/open-energy-transition/oet-data-bank/master/people/marthasnoopy_cropped.jpg",
    "linkedin_link": "",
    "mail_id": "firstname.lastname@openenergytransition.org",
    "name": "Snoopy",
    "twitter_link": "",
    "website_link": "https://www.example.com/snoopy"
}