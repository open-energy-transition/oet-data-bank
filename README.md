# OET Website and Handbook Team Data

This repository is designed to contain all team data for the OET website and handbook. New team members can easily be added here.

## Updating Instructions

1. **Add New Team Member**:
    - Create a new object with your name, designation, and description.
    - Add this object to the relevant data file.

2. **Upload Image**:
    - Upload an image of yourself to the `/people` directory.
    - Use the `crop_image.py` script located in the root directory to format your image for the website.
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
    "name": "Snoopy","mail_id": "",
    "twitter_link": "",
    "website_link": "https://www.example.com/snoopy"
}