package com.example.demo;

import org.springframework.boot.SpringApplication;
import org.springframework.boot.autoconfigure.SpringBootApplication;
import org.springframework.context.ConfigurableApplicationContext;

@SpringBootApplication
public class FirstApplication {

	public static void main(String[] args) {
		ConfigurableApplicationContext ac = SpringApplication.run(FirstApplication.class, args);
		Student st = ac.getBean(Student.class);
		System.out.println(st.getRoll());
		System.out.println(st.getName());
		}
}
