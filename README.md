# My-first-repository-on-GitHub
class Puppy():
    def __init__(self,name,favorite_toy):
        self.name = name
        self.favorite_toy = favorite_toy
        
    def play(self):
        print(self.name+" is playing with the "+self.favorite_toy)
        
marble = Puppy('marble', 'teddy bear')
marble.play()

onyx = Puppy('Onyx', 'lizard')
onyx.play()
