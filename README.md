AI CS is running rely on the prompt. AI will answer user's question based on the prompt we have gave to the AI. We should analyze the historical user question and summary the correct answer and write them down to the prompt.
We will use github to manage and control the propmt version. 
We should create a commit(pull) request for every change for the prompt that want to effect the prod AI agent. Every pull request should clearify the change topic(what new issue has been fixed), screenshots from PAPAGO platform to prove the AI has the new ability to answer the question. 

Prompt changging process: 
  real agent identify new type of issue needed to be resloved -> Add new FQA to prompt at PAPAGO TP AI CS - for prompt qa -> test by mocking the user question -> All good copy the prompt to the Github branch -> submit commit requst and provide the test evidance from papago screenshot -> Tag Hal via Teams to review merge -> Hal merge the propmt to the main branch and change the production prompt. 
  

The current system design is as following:
  User tap contact to support on Trucker Path -> lead to a UI that created by our FE team and AI powered by PAPAGO -> User submit questions and AI replys. -> Every time close the chat window a new zendesk ticket will be created and assign to AICS in zendesk -> Our real agent should monitor the AI ticket and follow the current escaltion method. 

  PAPAGO platform login: shared with Lianne and RJ  https://flow.papagoai.com/ feel free to test the AI performance via this mock agent: TP AI CS - for prompt qa
  
