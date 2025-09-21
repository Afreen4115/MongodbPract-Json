MongoDB Aggregation & Queries Cheatsheet
This repository contains a mongo.json file that serves as a cheatsheet for common and advanced MongoDB queries, with a focus on the Aggregation Framework.

About This File
The mongo.json file is a structured list of query examples. Each entry in the JSON array is an object containing:

"description": A plain-English comment explaining what the query does.

"query": The complete MongoDB Shell command as a string.

Topics Covered
This cheatsheet includes a wide range of operations, such as:

Grouping & Counting: $group, $sum, $avg

Filtering: $match

Shaping Documents: $project, $set, $addFields

Array & String Manipulation: $unwind, $concat, $toUpper

Conditional Logic: $cond, $switch

Joins: $lookup

Schema Validation: createCollection, collMod

And much more...

How to Use
You can browse the mongo.json file to find examples relevant to your needs. Copy the command from the "query" field and paste it directly into your MongoDB Shell (mongosh) or adapt it for your specific application driver.
