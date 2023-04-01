# 1st Person Shooter AI - Blueprints based  
This setup for basic shooter AI using blueprints.  
It uses AI Perception component that resides in AI controller class. 
With 2 perception config (sight and hearing).   
AI controller with filter and check every updated perception results.  
And apply state driven behaviour based on that. 
Where each of that state will be decorator in Behaviour Tree that defined AI action and tasks.  
This AI fit for shooter game and it also has stealth element.  