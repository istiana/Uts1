public class komputer 
{
	public int Processor;
	public int Memory;
	public int Storage;
	public class komputer(){
		int Processor=500;
			System.out.println("Kecepatan processor komputer")
		}
	class Notebook16 extends komputer{
		public int Baterai;
		public Notebook16 (int Pr,int Me,int St,int Bat){
			Processor = Pr;
			Memory = Me;
			Storage = St;
			Baterai = Bat;

	}
public void CetakSpesifikasi(){
	System.out.println("Kecepatan Processor Notebook16:" +Processor);
	System.out.println("Kapasitas Memory:" +Memory);
	System.out.println("Kapasitas Storage:" +Storage);
	System.out.println("Kapasitas Baterai:" +Baterai);
}
	public void dioverclock (int Pr){
		Processor=Pr;
	System.out.println("Notebook16 dioverclock dengan kecepatan processor:" +processor);
	
}
}