namespace IMC
{

    class Pessoa
    {
        //Atributos
        public double peso;
        public double altura;
        public double vldoimc;
        public string sexo;
        public string mensagem;

        public void CalcularIMC()
        {
            
            this.vldoimc = this.peso / (this.altura * this.altura);

            if (this.sexo.Equals("Masculino"))
            {
                if (this.vldoimc < 20.7)
                {
                    this.mensagem = "Abaixo do peso";
                }
                else if (this.vldoimc >= 20.7 && this.vldoimc <= 26.4)
                {
                    this.mensagem = "Peso normal";
                }
                else if (this.vldoimc >= 26.5 && this.vldoimc <= 27.8)
                {
                    this.mensagem = "Marginalmente acima do peso";
                }
                else if (this.vldoimc >= 27.9 && this.vldoimc <= 31.1)
                {
                    this.mensagem = "Acima do peso ideal";
                }
                else if (this.vldoimc > 31.1)
                {
                    this.mensagem = "Obesidade";
                }
            }
            
            else if (this.sexo.Equals("Feminino"))
            {
                if (this.vldoimc < 19.1)
                {
                    this.mensagem = "Abaixo do peso";
                }
                else if (this.vldoimc >= 19.1 && this.vldoimc <= 25.8)
                {
                    this.mensagem = "Peso normal";
                }
                else if (this.vldoimc >= 25.9 && this.vldoimc <= 27.3)
                {
                    this.mensagem = "Marginalmente acima do peso";
                }
                else if (this.vldoimc >= 27.4 && this.vldoimc <= 32.3)
                {
                    this.mensagem = "Acima do peso ideal";
                }
                else if (this.vldoimc > 32.3)
                {
                    this.mensagem = "Obesidade";
                }
            }
        }




    }
}
