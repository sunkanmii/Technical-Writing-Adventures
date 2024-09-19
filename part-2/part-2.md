What makes a good and well-structured API? Is it simplifying terms so users can understand? No, it's more than that.

A good technical documentation typically has the following characteristics:

1. Have a well-thought-out structure
    
2. Employ a great and consistent documentation strategy
    
3. Use simple language where necessary and don’t try to overcomplicate code descriptions
    
4. Has good examples and tutorials
    
5. Has good test cases
    

These amongst many others make up for good technical documentation and that also applies to API documentation.

Today, we will be looking at the basic structure of API documentation, particularly its resource description part.

# Basic Structure of an API Documentation

There are 5 common sections when writing API documentation and these are:

1. Resource description
    
2. Endpoints
    
3. Parameters
    
4. Request example
    
5. Response example and schema.
    

In the OAS (OpenAPI Specification), it is more along the lines of:

1. Metadata (specific to OAS)
    

2. Servers
    
3. Paths
    
4. Parameters
    
5. Request Body
    
6. Input and Output Models
    
7. Authentication
    
8. Examples (Parameters, Objects, and Properties)
    

We’ll go into its definition for most of these as we move forward.

Let’s look into API Reference and its differences via this table below:

| API Reference | Tutorials/User Guides |
| --- | --- |
| Usually concise, short and to the point. | Usually long and elaborate with enough details and explanation |
| Fast and easy to read at a glance to understand what the API does | Slower, but provides a deeper understanding of the API |

Resource descriptions and endpoint descriptions follow the same format as API reference. They are usually 1 - 3 sentences long and don’t go into so much detail like the tutorials that explain the simplest concepts to the most complex ones. Tutorials are good, but leaving formats as they are has its merits and its demerits.

Some technical writers often use the same words to describe a “thing” in technical documentation, but I want to be as clear and as simple as possible. Hence, for clarity’s sake, just keep in mind when reading these articles I put out:

> No two English words mean exactly the same thing and are 100% synonymous. Even if they do exist, it’s very rare

Meaning, (for example) that when I say “resource”, it’s not the same as “endpoint”. You get? I want to go into detail and help you understand these concepts as much as I understand them. So help me out by commenting on how these articles can be improved. It goes a long way!

# Examples of Resource Description

1. Twilio Message Resource
    
    ![Twilio Message Resource description](https://cdn.hashnode.com/res/hashnode/image/upload/v1726784336081/1d8945d7-12f3-49f2-81fa-edab47f1776e.png align="center")
    
    You know how I said it’s resource descriptions are usually concise? And the above picture doesn’t follow it. Okay, hear me out. Mega companies like Twilio may decide to take a different approach like their Messaging Resource in particular which I think it’s still okay.
    
2. GitHub Check Run Resource
    
    ![GitHub Check Runs Resource](https://cdn.hashnode.com/res/hashnode/image/upload/v1726784537111/44603688-d2f9-4016-bb53-73b4f655b517.png align="center")
    
    GitHub Check Runs Resource follows the usual format and style of a resource description.
    

Notice a difference between how resources typically contain a list of endpoints rather than just a single one. That’s something to keep in mind when differentiating between an endpoint and a resource.

I hope you enjoyed today’s adventure. I do hope you learned a thing or two though. If you did, let me know in the comments section below or just like the article so I know you read till this point. :) Thank you for your time and I’ll see you in the next one!