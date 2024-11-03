public class DayNightManager : MonoBehaviour
{
    private int weekday = 1;
    private bool isDay = true;

    public int GetWeekday()
    {
        return weekday;
    }

    public bool GetIsDay()
    {
        return isDay;
    }

    public void ProgressDay()
    {
        if (isDay)
        {
            isDay = false;
        }
        else
        {
            isDay = true;
            weekday = (weekday % 7) + 1;
        }
    }
}

