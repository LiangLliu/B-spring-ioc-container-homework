* @Component 已经可以支持声明一个 bean 了，为何还要再弄个 @Bean 出来？

    * @Component注解的bean是由SpringBoot全权负责的，使用@Configuration配合@Bean这种方式注入bean,一定程度上实现了定制化。
    * @Component是类级别的bean注入，而@Configuration配合@Bean是注解在方法上的，它可以定义方法级别的Bean。
