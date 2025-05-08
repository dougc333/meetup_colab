Source code for pypi https://pypi.org/project/meetup-colab/

https://github.com/dougc333/meetup_colab

In colab terminal 
```
> pip install meetup-colab
```
or in colab cell
```
!pip install meetup-colab
```

In colab cell

```
from meetup-colab import nvidia
nvidia.update_12_4()
nvidia.install_nemo()
```

Warning: takes 10-15m! 
Adding mamba to fix the LLM error takes an additional 17m on top of the existing 10-15m. 
Adding Apex takes an additional 10m. Both Apex and mamba builds were omitted for time. 
