# RapidJSON
include(ExternalProject)
ExternalProject_Add(rapidjson_github
        GIT_REPOSITORY "https://github.com/Tencent/rapidjson.git"
        GIT_SHALLOW 1
        GIT_COMMIT "663f076")