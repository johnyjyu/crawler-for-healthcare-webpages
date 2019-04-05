# medicalBot
part of medical chat bot wechat17intern
1, crawl and parse the following four websites for medical pages. 
http://baike.baidu.com/wikitag/taglist?tagId=75953
科学百科疾病症状分类(共7252个)

http://baike.baidu.com/wikitag/taglist?tagId=75954
科学百科药物分类(共8155个)

http://baike.baidu.com/wikitag/taglist?tagId=75956
科学百科中医药分类(共4105个)

http://baike.baidu.com/wikitag/taglist?tagId=75955
科学百科诊疗方法分类(共2418个)


2,

http://python-guide-pt-br.readthedocs.io/en/latest/dev/virtualenvs/
count number of files: 
grep -Rl "curl" ./ | wc -l

data json file format:
{"title":{
         "summary":"...",
         "cause":"...",
         "treatment":"..."
    }
}

{"data":[{"title":"XXX", "paragraphs":[{"context":"", "qas":[
    {"answers":[{"answer_start":255, "text":"west"}], "question":"YYY?", "id":"5735cc33012e2f140011a069"}, 
    {"answers":[{"answer_start":255, "text":"west"}], "question":"YYY?", "id":"5735cc33012e2f140011a069"}, 
    
    ]}]}]}


Setting the Default Java File Encoding to UTF-8:

    export JAVA_TOOL_OPTIONS=-Dfile.encoding=UTF8

server.228

git
jira

codeReview
unitTest
