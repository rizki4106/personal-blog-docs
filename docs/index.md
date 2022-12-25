# Welcome onboard
This is the docummentation for bloging platform
## Requirements
* Admin Requirements

    | Name | Description |
    | ---- | ----------- |
    | CRUD blog | able to `create`, `read`, `update` and `delete` the blog post |
    | Add Tag | before the blog post published the system must be asked for the tag e.g ai, finance and etc |
    | Preview Mode | Before the blog post published or during edit should be available preview mode |
    | Login | Before make blogpost admin must be logged in using onetime password that sended to email and token that sended has an exipration time |
    | Add Admin | Admin can add another admins |
    | Edit or delete | Admin can edit or delete blog post from the list of blog post in home page or another page as seen as user |
    | Go to Site | Admin can directly go to online site from the dashboard |

* User Requirements

    | Name | Description |
    | ---- | ----------- |
    | Home | Home page that contain recommendation blog posts |
    | Search | User can search any blog post that they want |
    | Save Post | User can save blog post and the data is stored in `local storage`|
    | Share Button | User can share any blog post to other social media platform |

* System Requirements

    | Name | Description |
    | ---- | ----------- |
    | Next.Js | The frontend must be using `next.js` framework |
    | Go - Languange | For the backend must be using **`Go - Languange`** |
    | JWT Token | when admin logged in they can edit or update blog post and when they send request to do that they should be send the jwt token in header requests |
    | Admin Info | When admin loggin the info must be store in cookie with JWT token for 30 days |
    | Endless Scoll | When user reach out the bottom of the content then system must be load another content |
    | About Page | Show information about who i am and the contact |