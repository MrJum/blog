    
    myscrm_cms
    -- 文案内容表
    select * from myscrm_copywriting_content where content like '%晚上好%';
    -- 文案上面点击喜欢，会保存在这张表，如果取消喜欢，这条数据会删除
    select * from myscrm_copywriting_like where content_id='7' and user_id='39d496c7-ed5f-6972-f4a9-19f5ab9eeb2c';
    -- APP点击分享到朋友圈，share数值为+1
    select * from myscrm_copywriting_share where content_id='7';
    
