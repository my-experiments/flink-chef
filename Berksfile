source 'https://supermarket.chef.io'

metadata

cookbook 'java'
cookbook 'kagent', github: 'karamelchef/kagent-chef'
cookbook 'apache_hadoop', github: 'my-experiments/apache-hadoop-chef'
cookbook 'hops', github: 'hopshadoop/hops-hadoop-chef', branch: 'master'
cookbook 'ndb', github: 'hopshadoop/ndb-chef', branch: 'master'

group :test do
  cookbook 'apt'
end

