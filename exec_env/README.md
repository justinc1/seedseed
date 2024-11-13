# seedseed Execution Environment

The seedseed execution environment includes `infra.ee_utilities` role,
to allow building other EE using `infra.ee_utilities.ee_builder`.

To build this EE:

```
cp -i exec_env/secrets.yml.template exec_env/secrets.yml
nano exec_env/secrets.yml

ansible-playbook -e @exec_env/secrets.yml exec_env/build_seedseed_ee.yml
```
