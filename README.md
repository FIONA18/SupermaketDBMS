# Supermarket DBMS
Supermarket Database Management System using java


This is Supermarket.java file

package supermarket;

import javafx.application.Application;
import javafx.stage.Stage;

public class Supermarket extends Application {
    
    @Override
    public void start(Stage primaryStage) {
        new HomePage().setVisible(true);
    }

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        launch(args);
    }
    
}
