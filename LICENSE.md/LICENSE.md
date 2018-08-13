import java.util.HashMap;
import java.util.Map;
import java.util.Map.Entry;
import java.util.Set;

public class Test {

	public static void main(String[] args) {
	
		Map map = new HashMap();
		map.put("小明", "杏花村");
		map.put("冰冰", "东玩");
		map.put("张三", "魔都");
		//遍历map
		Set<Entry> entrys = map.entrySet();
		for(Entry en : entrys){
			Object key = en.getKey();
			Object value = en.getValue();
			System.out.println(key+"++++"+value);
		}
	
	}

}


