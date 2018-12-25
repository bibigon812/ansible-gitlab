# ansible-gitlab

``` yml
gitlab_omnibus_config: |
  external_url 'https://gitlab.example.com/'
  gitlab_rails['lfs_enabled'] = true
  gitlab_rails['smtp_enable'] = true
  gitlab_rails['smtp_address'] = 'relay.example.com'
  gitlab_rails['smtp_port'] = 25
  gitlab_rails['smtp_domain'] = 'example.com'
  gitlab_rails['smtp_tls'] = false
  gitlab_rails['smtp_openssl_verify_mode'] = "none"
  gitlab_rails['smtp_enable_starttls_auto'] = false
  gitlab_rails['smtp_ssl'] = false
  gitlab_rails['smtp_force_ssl'] = false
```
