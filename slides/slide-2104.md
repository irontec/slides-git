### Ejemplo de configuración

```ruby
external_url 'https://git.example.com'
unicorn['worker_timeout'] = 180
nginx['client_max_body_size'] = '2250M'
gitlab_pages['enable'] = true
pages_external_url "http://git.example.com/"
gitlab_rails['gitlab_email_from']='gitlab@example.com'
gitlab_rails['ldap_enabled'] = true
gitlab_rails['ldap_servers'] = YAML.load <<-EOS
main:
  label: 'LDAP'
  host: 192.168.1.10
  port: 389
  uid: 'uid'
  method: 'plain'
  base: 'ou=users, dc=example, dc=com'
  user_filter: ''
EOS
```
