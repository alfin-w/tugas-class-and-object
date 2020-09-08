<?php
class Pesawat{
	public $nama,$merk,$warna,$bom,$tembak;

	public function jatuhkanbom(){
		return "Bom Telah Dijatuhkan";
	}
}

class pesawaTempur extends Pesawat{
	public $turbo = false;

	public function musuhtembak(){
		$this->turbo=true;
		return "Musuh Sudah Ditembak";
	}
}

$pesawatu = new pesawaTempur();
echo $pesawatu->jatuhkanbom();
echo "<br>";
echo $pesawatu->musuhtembak();


?>
