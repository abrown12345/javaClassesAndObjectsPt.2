# javaClassesAndObjectsPt.2
public class car {
	private int year;
	private String model; 
	private String make;

	public car() {

	}

	public car(int year, String model) {
		this.year=year;
		this.model=model;
	}
	
	public car(int year, String model, String make) {
		this.year=year;
		this.model=model;
		this.make=make;
	}
	
	public int getYear() {
		return year;
	}
	
	public void setYear() {
		this.year=year;
	}
	
	public String getModel() {
		return model;
	}
	
	public void setModel() {
		this.model=model;
	}
	
	public String getMake() {
		return make;
	}
	
	public void setMake() {
		this.make=make;
	}
	
	public boolean isGas() {
		return true;
	}
	
	public String carLine() {
		return "Any car can get you where you need to go. A special car gets you there with a smile on your face.";
	}
	
	public String specialAdds(String list) {
		return list;
	}
	public static void main(String[] args) {
		car Car= new car(1996, "Nissan", "300ZX");
		System.out.println("leather seats");
	}

}
