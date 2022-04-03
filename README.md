
public class Employee {
	private int id;
	private String name;
	private String address;

	public Employee(int id,String name,String address) {
		this.id=id;
		this.name=name;
		this.address=address;
		
		
	}
	
	@Override
	public String toString() {
		return "Employee [id=" + id + ", name=" + name + ", address=" + address + "]";
	}

	public static void main(String[] args) {
		
	
	Employee employee=new Employee(22, "vansaj", "delhi");
	Employee employee1 =new Employee(3, "bhai", "mumbai");
	System.out.println(employee1);
	System.out.println("***********");
	System.out.println(employee);
	}
	
	
}

