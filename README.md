# java-pattren
package javaaaaa;

public class rumah {

private String kamarMandi;
private String ruangTamu;
private String tempatTidur;

// variabel opsional
private String kolamRenang;
private String garasi;

 public Rumah(String kamarMandi, String ruangTamu, String tempatTidur, String garasi, String kolamRenanga) {
	this.kamarMandi = kamarMandi;
	this.ruangTamu = ruangTamu;
	this.tempatTidur = tempatTidur;
	this.garasi = garasi;
	this.kolamRenang = kolamRenang;
 }
 public String getkamarMandi() {
	 return kamarMandi;
 }
 public String getruangTamu() {
	 return ruangTamu;
 }
 public String gettempatTidur( ) {
	 return tempatTidur;
 }
 public String garasi() {
	 return garasi;
 }
 
 public String getkolamRenang() {
	 return kolamRenang;
 }
 
 public static class RumahBuilder {
	 private String kamarMandi;
	 private String ruangTamu;
	 private String tempatTidur;
	 Private String garasi;
	 private String kolamrenang;
	 //optional parameter
	 private String garasi;
	 private String kolamRenang;
	 
	 public rumahBuilder(String kamarMandi, String ruangTamu, String TempatTidur) {
		 this.kamarMandi = kamarMandi;
		 this.ruangTamu = ruangTamu;
		 this.tempatTidur = tempatTidur;
	 }
	 public RumahBuilder setgarasi(String garasi) {
		 this.garasi = garasi
				 return this;
	 }
	 
	 public RumahBuilder setkolamRenang(Strimh kolamRenang) {
		 this.kolamRenang =kolamRenang
				 return this;
	 }
	 public Rumah build();
	 Return new Rumah(this);
	 
		 
	 }
 }

}

