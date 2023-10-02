import java.awt.*;
import javax.swing.JFrame;

public class main {

    public static void main(String[] args){
        JFrame f = new JFrame();
        f.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
        f.setTitle("kek");

        f.add (new GraphicsSurface());

        f.setSize(512, 512);
        f.setLocationRelativeTo(null);
        f.setVisible(true);
    }
}
