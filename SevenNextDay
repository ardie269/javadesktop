# javadesktop
JavaSourceCode
/*
 * To change this template, choose Tools | Templates
 * and open the template in the editor.
 */
package learnjava;

import java.util.ArrayList;
import java.util.Calendar;
import java.util.Collection;
import java.util.Date;
import java.util.GregorianCalendar;
public class SevenNextDay {
    public static void main(String[] args) {
        Calendar calendar = new GregorianCalendar();
        Collection collectionOfDays = new ArrayList();
        
        for(int i=0; i<7; i++){
            Date currentDate = new Date();
            calendar.add(Calendar.DATE,1);
            currentDate.setTime(calendar.getTimeInMillis());
            collectionOfDays.add(currentDate);    
        }
        
        for(Object oneDay:collectionOfDays){
            System.out.println("The next day is : "+oneDay);
        }
    }
}
