# Resetting the Jupiter Notebook Kernal
 import IPython
* Retrieve the current IPython application instance

 
 app = IPython.Application.instance()
 * perform a complete shutdown of the current IPython kernal including restarting the kernal , it will help the environment to access new packages

  
 app.kernal.do_shutdown(True)
# TextAnaysisPipeline-Agent
