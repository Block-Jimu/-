实验目的
初步了解分析系统需求，从学生选课角度了解系统中的实体及其关系，学会定义类中的属性以及方法；
掌握面向对象的类设计方法（属性、方法）；
掌握通过构造方法实例化对象；
学会使用数组。
业务要求
学校人员分为“教师”和“学生”，教师教授“课程”，学生选择“课程”。
每名教师可讲授多门课程，每名学生可选修多门课程。
多门课程，可用课程数组形式表达。
对象示例：
教师（编号、姓名、性别、所授课程）
学生（编号、姓名、性别、所选课程）
课程（编号、课程名称、上课地点、时间）
实验要求
1.编写上述实体类以及测试主类
2.在测试主类中，实例化多个类实体，模拟
1）教师开设某课操作；
2）学生选课操作、退课操作
3）打印学生课表信息（包括：编号、课程名称、上课地点、时间、授课教师等）
3.编写实验报告。
源代码
package one;
class Fish{
 int weight;
}
class Lake{
 Fish fish;
 void setFish(Fish s){
  fish = s;
 }
 void eat(int n){
  fish.weight = fish.weight + n;
 }
}
class FishandLake{
 public static void main(String[] args) {
  Fish niqiu = new Fish();
  System.out.println(niqiu.weight); 
  Lake dongtinghu  = new Lake();
  Lake xihu        = new Lake();
  taihu.setFish(niqiu);
  taihu.eat(15);
  System.out.println(niqiu.weight); 
  System.out.println(taihu.fish.weight); 
  dongtinghu.setFish(niqiu);
  dongtinghu.eat(8);
  System.out.println(niqiu.weight); 
  System.out.println(dongtinghu.fish.weight); 
  xihu.setFish(niqiu);
  xihu.eat(10);
  System.out.println(niqiu.w
