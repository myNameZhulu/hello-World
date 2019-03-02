page com.newer.boot.emp
/**
 *  员工实体类
 *    （练习Git） 
 *  作者：朱璐
 */
public class emp{

   //员工id
    private Integer id;
    //员工姓名
    private String ename;
    
    public Integer getId(){
    return id;
    }
    public void setId(Integer id){
    this.id=id;
    }
    
    public String getEname(){
    return ename;
    }
    
    public void setEname(String ename){
    this.ename=ename;
    }
}
