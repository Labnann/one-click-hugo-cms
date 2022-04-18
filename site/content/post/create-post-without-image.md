---
title: Create Post Without Image
date: 2022-04-18T20:28:30.393Z
description: Attempt to create post without image
---
In case you are interested, here is the last payload snippet:
```
{
    "branch": "main",
    "action": "persistEntry",
    "params":
    {
        "branch": "main",
        "dataFiles":
        [
            {
                "path": "site/content/post/create_post_api_test.md",
                "slug": "create_post_api_test",
                "raw": "---\ntitle: Create_Post_Api_Test\ndate: 2022-04-18T19:44:45.575Z\ndescription: The post is created to test what info is sent to the server to create a post.\nimage: img/173641_latest-hd-wallpapers_1600x1000.jpg\n---\nA image is put here, cause why not '-'"
            }
        ],
        "assets": [],
        "options":
        {
            "newEntry": true,
            "commitMessage": "Create Post “create_post_api_test”",
            "collectionName": "post",
            "useWorkflow": false,
            "unpublished": false,
            "status": "draft"
        }
    }
}
```                