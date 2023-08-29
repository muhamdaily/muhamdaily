```ini
from github.profile import ReadMe
class muhamdaily ( ReadMe ) :
    def __init__ ( self ) :
        self.username  = "MuhamDaily"
        self.location  = "Indonesia"
        self.discord   = "@muhamdaily"
        self.languages = [ "PHP", "Javascript", "C#", "Java" ]
    def about ( self ) :
        print( f"Hi, I'm {self.username}. Contact me on {self.discord}" )
me = muhamdaily()
me.about()
```
