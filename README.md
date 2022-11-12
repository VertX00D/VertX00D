```python
class Attributes(Vert):
	def __init__(self) -> None:
	    pass
	
	@staticmethod
	def life(self) -> tuple:
		langs         = ['English', 'Turkish', 'France']
		nationalities = self.langs.remove('French', 'English').append('Korean')
		age           = 17
		
		return langs, nationalities, age
	
	@staticmethod
	def coding(self) -> tuple:
		langs = {
			'expert':   ['python'],
			'intermediate': ['python'],
			'learning': ['js', 'html', 'css']
		}
		specialities  = [discord bots']
		environnement = ['vscode']
		
		return langs, specialities, environnement
```
