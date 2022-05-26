namespace IMC
{
    
    public partial class Form1 : Form
    {
        InitializeComponent();
    }

    Pessoa mc = new Pessoa();
    private void button1_Click(object sender, EventArgs e)
    {
        //Calcular
        mc.altura = double.Parse(txtAltura.Text);
        mc.peso = double.Parse(txtPeso.Text);
        mc.sexo = cmbSexo.Text;

        mc.calcularIMC();

        //Monstrar Dados
        MessageBox.Show("Seu IMC é:" + " " + mc.vldoimc + "," + "você está " + " " + mc.mensagem);
    }

    private void button2_Click (object sender, EventArgs e)
    {
        //Limpar
        txtAltura.Text = "";
        txtPeso.Text = "";
        cmbSexo.Text = "";
    }

} 
