# 02 Capstone Project - Enhancing a Community Library Website
This is my second Capstone project on the DevOps Self-paced Foundation course.

As part of the development team tasked with enhancing the `Greenwood Community Website`, I have added a `Book Reviews` page and also updated the `Events` page.

## Creating and Cloning a Repository on Github
This was done by creating a repository on my remote github account and cloning it on my local machine into the `GreenwoodLibrary` directory.

![cloning_remote_site](./cloning.png)

## Ensuring the following HTML files exist
Using the `vim` command, the following html files were created and contents written inside as shown in the image below.

home.HTML


about_us.HTML


events.HTML


contact_us.HTML


![html_files](./html_files.png)

## Staging
Before staging, I ran a `git status` command to show new updates.
![git_status](./3git_status.png)

The new updates are shown in red.

Then I did the `git add .` command to stage all.
![git_add_command](./3git_add.png)


Then I did `git status` again to confirm the updates have been staged.
![confirm_staging](./4git_staus.png)


The staged updates are shown in green.

## Commit
I ran the `git commit` command with the message `"commit task"`.

![git_commit](./5git_commit.png)

## Push
I ran the `git push` command.
![git_push](./6git_push.png)


## Adding Book Reviews Branch
First, I created a branch named `add-book-reviews`
![book_reviews](./7book_review_branch.png)


Then I created an html file with `vim` named "book_reviews.html"
![book_reviews_html](./8book_review_html.png)


I staged all the recent updates with the `git add .` command.
![staging_all](./9git_add.png)

I commited the changes with the message "Add book reviews section"
![commit](./10git_commit.png)



Then I pushed the branch changes to github
![push](./11git_push.png)


## Raising a Pull Request
I navigated to "add-book-reviews" branch under the main branch.


![pull_request](./12pull_request1.png)



I initiated and confirmed the pull request as sequentially shown below.
![pull_request](./13pull_request2.png)




![pull_request](./14pull_request3.png)

## Merging the work to main branch
After confirming the branch has no conflicts with the base branch, I merged it with the main branch as shown below.

![merge](./15merge_pull_request.png)




![confirm_merge](./16confirm_merge.png)




The image below shows that merge was successful.
![merge_success](./17successful_merge.png)

## Update Events Branch

I swicthed to a new branch named `update-events` branch with the `git checkout -b update-events` as shown below.
![update_events](./18Snipaste_2024-10-11_06-16-37.png)


I pulled from the main branch for the latest changes with the `git pull origin main` command
![pull](./19pull_events_branch.png)


Then I initiated a pull request as shown below.
![pull_request](./22events_merge_pull_request.png)

I added a description that `the events page was updated`
![upadte](./23events_pull_request.png)

I confirmed it.
![confirm](./24confirm_merge_events.png)
