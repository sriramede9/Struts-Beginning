# Struts-Beginning
Struts Beginning

# Sample clasee
#Struts.xml in class path 
# web.xml filters to access struts before xml

## Adding name space

http : //ip:port/<webapp>/<namespace>/actionname.action

`<package name="com.sri.struts" namespace="/tutorials" extends="struts-default">  
  
<action name="getTest" class="com.sri.struts.TestStrutAction">  
<result name="success">/welcome.jsp</result>  
<result name="error">/error.jsp</result>  
</action>  
  
</package> `