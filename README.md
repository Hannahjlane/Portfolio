# Portfolio

<!DOCTYPE html>
<html>

<h1>ABOUT ME</h1>

<p>I am a rising junior at Los Gatos High School. I am involved in Yearbook, and currently hold the title as Editor. I enjoy all outdoor activities, including; boating, skiing, swimming, hiking, golfing and traveling. I love to write, design layouts, take pictures and spend time with my family. I am an organized, kind, helpful, passionate person. I am involved in many non-profit organizations, and enjoy giving my time on a weekly basis. I complete 100+ hours/year. I am also a technology guru. I love exploring new technology... and am quite good at it. As a detail-oriented person, I am currently working on more design projects, I enjoy graphic and interior design-- plus I have a great eye for colors and position. I live with my dad, mom, ll year-old sister Natalie and 2 orange tabbies, Oliver and Tigger. As a 16 year-old, I love to hangout with my friends, and have fun. I am currently interested i coding -- as it’s the now and the future. I enjoy using code, and have worked and produced many projects with the support of the Microsoft staff.

Thanks,

Hannah Lane</p>


<img src="http://www.mercurynews.com/wp-content/uploads/2016/10/slgw1014house01.jpg?w=486" alt="Helping Others" style="width:100px;height:100px;">

<img src="https://media.giphy.com/media/TKqXCyRwqf0DC/giphy.gif"/>

<img src="https://media.giphy.com/media/l0HFkso2E6ty4naCs/giphy.gif"/>

import javax.swing.*;
import java.awt.*;
import java.awt.event.*;

public class example {

public static void main (String[] args){    
  JFrame frame = new JFrame("Test");
  frame.setVisible(true);
  frame.setSize(500,200);
  frame.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);

  JPanel panel = new JPanel();
  frame.add(panel);
  JButton button = new JButton("hello agin1");
  panel.add(button);
  button.addActionListener (new Action1());

  JButton button2 = new JButton("hello agin2");
  panel.add(button2);
  button.addActionListener (new Action2()); 
}
static class Action1 implements ActionListener {        
  public void actionPerformed (ActionEvent e) {     
    JFrame frame2 = new JFrame("Clicked");
    frame2.setVisible(true);
    frame2.setSize(200,200);
    JLabel label = new JLabel("you clicked me");
    JPanel panel = new JPanel();
    frame2.add(panel);
    panel.add(label);       
  }
}   
static class Action2 implements ActionListener {        
  public void actionPerformed (ActionEvent e) {     
    JFrame frame3 = new JFrame("OKNO 3");
    frame3.setVisible(true);
    frame3.setSize(200,200);

    JLabel label = new JLabel("kliknales");
    JPanel panel = new JPanel();
    frame3.add(panel);
    panel.add(label);
  }
}   
}

</body>
</html>
