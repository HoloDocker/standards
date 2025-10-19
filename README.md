# The Structure

## The image descriptor

    {
      "hd_version": "1.0",
      "hd_type": "image",
      "name": "image name",
      "repo": "repository", // if missing, default is dockerhub
      "hash": "<image hash>", // if missing it is not checked
      "implements": ["s3", "openapi"] //standard interfaces the image provides
      "provides": [
      ], 
      "requires": [
      ]

    }

## interface descriptor

    {
      "hd_version": "1.0",
      "hd_type": "interface",
      "name": ""
    }

## Organization Descriptor

    {
      "hd_verson": "1.0",
      "hd_type": "organization",
      "name": "org name",
      "services": [{
        "name": "name",
        "image": "image",
        "position": [x,y],
        
      }, {...}],
      "units": [
      ], 
      "connectors": [
        
      ]
    }
