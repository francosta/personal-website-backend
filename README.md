# Overview

This is the codebase for the backend of my personal website, www.franciscocosta.me.
It was developed using Strapi.

# Resources

There are two types of static content-types, LandingPage and About. Other content-types are BlogPost and Project. All are managed entirely through the Strapi CMS interface.

There are modular components for Media content and the Technology elements used in Project posts.

# Webhooks

There is a webhook which calls on the deployment endpoint to trigger a new build of the website, every time any of the content-types is updated, deleted or created.

# Media Assets

Media assets are hosted and managed using Amazon Web Services, through the [Strapi AWS S3 plugin](https://www.npmjs.com/package/strapi-provider-upload-aws-s3).
