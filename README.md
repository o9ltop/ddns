# ddns

# Prepare
## Install Dependency Package
~~~ python
pip install -r requirements.txt
~~~
## Set Key
get your acdcess key
![getKey.png](img%2FgetKey.png)

Set in environment variables

<details>
<summary>windows</summary>

![setEnvVar.png](img%2FsetEnvVar.png)

</details>

<details>
<summary>linux</summary>


~~~
export ALIBABA_CLOUD_ACCESS_KEY_ID=YOU_ID
export ALIBABA_CLOUD_ACCESS_KEY_SECRET=YOU_KEY
~~~

</details>

# run
~~~
python src/ddns.py
~~~