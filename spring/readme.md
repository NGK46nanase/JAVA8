
Spring comes with several container implementations that can be categorized into two distinct types.

 1 Bean factories
   org.springframework.beans.factory.BeanFactory interface
 2 Application contexts 
   org.springframeword.context.ApplicationContext interface
    
     AnnotationConfigApplicationContext - loads a spring application context from on or more Java-based configuration classes
     
     AnnotationConfiWebApplicationContext - loads a spring web application context from on or more Java-based configuration classes
     
     ClassPathXmlApplicationContext - loads a context definition from on e or more XML files located in the classpath, treating context-definition files as classpath resources
     
     FileSystemXmlApplicationContext - loads a context definition from one or more XML files in the filesystem
     
     XmlWebApplicationContext - loads context definitions from one or more XML files contained in a web application
     
 3 Bean life cycle
 
 instantiate -> populate properties -> BeanNameAware's setBeanName() -> BeanFactoryAware's setBeanFactory() -> ApplicationContextAware's -> setApplicationContext() 
 -> PreInitialization BeanPostProcess -> InitializingBean's afterPropertiesSet() -> Call custom init-method -> Post-Initialization BeanPostProcessors 
 
 Bean is ready to use
 --------------------
 Container is shut down
 
 DisposableBean's destroy -> Call custom destroy-method
     
     
     
     
