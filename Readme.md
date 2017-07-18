docker run -p 18080:8080 -v /Users/stevedavis/Downloads/derby_data:/artifactory/data mattgruter/artifactory

docker run -p 18080:8080 -v /Users/stevedavis/Downloads/derby_data:/artifactory/data -v /Users/stevedavis/.m2:/m2 mattgruter/artifactory
