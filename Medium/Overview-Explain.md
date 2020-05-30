How do I build a mini-medium, so that ....?

FRONTEND 
    React.js, Gulp, Webpack, NPM, Templates...
MIDDLEND 
    Data Model(graphql), Interactions, Behaviour, Communication
    GraphQl Server
BACKEND + API
    Node.js, Django, PHP .../ Network Stack + CDN + ADN
DATABASE
    PostgresQL, MongoDB

Data Model 

type Blog {
    title : "sadfasdf"
    content : "aslkdjfnkljn. ionmlonmsd"
    author : "asdfasdf", 
    ...
}

fetch("https://backend.medium.com/getBlogs", GET Request) -> JSON -> JSON.PARSE -> get back an Array[Blogs]

fetch("https://backend.medium.com/saveBlog", POST Request, Obj<Blog>) -> Convert to JSON -> SEND TO BACKEND 

postgres.createDoc("kjasdbklfjbn", Obj<Blog>) 

mongo.query(fetch_blogs, author_id, claps > 5)

Author-id | Blog-Id      Blog-Id | Comments | Clap Count Analytics , jjj ... ML

mongo.getDoc("kjasdbklfjbn") 

https://backend.medium.com/editBlog/jkr9834jr908jfnm
https://backend.medium.com/deleteBlog/jkr9834jr908jfnm
https://backend.medium.com/getBlogs/match?q=l;kmdsamf&&j=ljksndafl;n


RESTful -> VERBS HTTP GET, PUT, POST, DELETE

GRAPHQL {
    postgres_url : ec2.postgres.com
    dynamodb : ec2.mongo.com
}

```FRONTEND
    fetch("https://microsrevice.medium.com/_graphql", getAllBlogs, GET REQUEST)
    fetch("https://microsrevice.medium.com/_graphql", saveBlogs,  POST REQUEST, Obj<Blog>)
    fetch("https://microsrevice.medium.com/_graphql", editBlog, id, PUT REQUEST, Obj<Blog>)
    fetch("https://microsrevice.medium.com/_graphql", deleteBlog, id, DELETE REQUEST, Obj<Blog>)
    fetch("https://microsrevice.medium.com/_graphql", getSpecificBlog, id, clapCount, GET REQUEST)
```

```BACKEND
    microservice1 {
        requestHandler.get("https://backend.medium.com",  queryString) async => {
            await let result = mongo.query(queryString)
            return HTTPResponse("Status : 200", JSON.stringify(result))
        }
    }  

    microservice2 {
        requestHandler.post("https://backend.medium.com",  queryString, data) async => {
            await let result = mongo.createDoc(queryString, data)
            return HTTPResponse("Status : 200", JSON.stringify(result))
        }

        requestHandler.put("https://backend.medium.com",  id, queryString, data) async => {
            await let result = mongo.updateDoc(id, queryString, data)
            return HTTPResponse("Status : 200", JSON.stringify(result))
        }
    }
    
    microservice3 {
        requestHandler.delete("https://backend.medium.com",  id, queryString, data) async => {
            await let result = mongo.deleteDoc(id, queryString, data)
            return HTTPResponse("Status : 200", JSON.stringify(result))
        }

        requestHandler.get("https://backend.medium.com",  id, clapCount, queryString) async => {
            await let result = graphql.query( graphql_endpoint, {
                id : id, 
                query : querystring => {
                    this.clapCount > clapCount
                }
            })
            return HTTPResponse("Status : 200", JSON.stringify(result))
        }
    }


    graphql_endpoint : https://medium.graphql.com
```

<div>{Blog.Title}</div>
