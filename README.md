# Hello, World! ![](https://cinni.net/images/web/world.gif)


```python
class sneeppy:

    def __init__(self):
        self.username = 'sneeppy'
        self.name = 'Винидиктов Паавел'
        self.position = 'Data Scientist'
        self.telegram = '@sneeppy'
        self.code = {
            'languages': ['Python', 'SQL', 'C++'],
            'database': ['PostgreSQL', 'MySQL', 'QDrant'],
            'devops': ['Docker', 'Linux', 'GitHub Actions'],
            'tools': [
                'Pandas', 'NumPy', 'PyTorch', 'TensorFlow', 
                'LangChain', 'LangGraph', 'XGBoost'
                ],
        }

    def __str__(self):
        return f'{self.name} | {self.position}'


if __name__ == '__main__':
    me = sneeppy()
    print(me)
```
