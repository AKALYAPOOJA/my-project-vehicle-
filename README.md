package net.oasismgt.tin_service_generation.local.constants;


public enum LineOfBusiness{
        _210("210","Repair of machinery"),
	_100("100","Repair of electronic and optical equipment"),
	_3310("3310","Repair of electrical equipment"),
	_313("313","Repair of transport equipment, except motor vehicles");

private LineOfBusiness(String code,String title){
		this.code=code;
		this.title=title;
	}
	
	public String getTitle() {
		return title;
	}
	public void setTitle(String title) {
		this.title = title;
	}
	
	public String getCode() {
		return code;
	}
	public void setCode(String code) {
		this.code = code;
	}
	
	private String title;	
	private String code;
	
	public String toString(){
		return title;
	}
	
}
