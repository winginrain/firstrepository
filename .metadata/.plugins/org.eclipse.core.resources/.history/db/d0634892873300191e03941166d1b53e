package com.gc.test;
import org.springframework.context.ApplicationContext;
import org.springframework.context.support.FileSystemXmlApplicationContext;
import com.gc.action.HelloWorld;
public class TestHelloWorld {
	public static void main(String[] args) {
		ApplicationContext actx=new FileSystemXmlApplicationContext("src/config.xml");
		HelloWorld HelloWorld=(HelloWorld) actx.getBean("HelloWorld");
		System.out.println(HelloWorld.getMsg());
	}
}
