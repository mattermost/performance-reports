### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.CreateSidebarCategory | avg | 43ms | 177ms | 134ms | 312.11
| RoleStore.GetByNames | avg | 12ms | 27ms | 15ms | 125.39
| PostStore.Delete | avg | 40ms | 84ms | 44ms | 108.80
| ProductNoticesStore.ClearOldNotices | avg | 30ms | 60ms | 30ms | 101.09
| PostPersistentNotificationStore.Get | avg | 5ms | 8ms | 3ms | 65.49
| UserAccessTokenStore.GetByToken | avg | 8ms | 13ms | 5ms | 58.85
| StatusStore.SaveOrUpdate | avg | 18ms | 28ms | 10ms | 56.12
| RoleStore.ChannelHigherScopedPermissions | avg | 9ms | 14ms | 5ms | 53.01
| DraftStore.DeleteDraftsAssociatedWithPost | avg | 12ms | 18ms | 6ms | 49.72
| EmojiStore.GetMultipleByName | avg | 8ms | 12ms | 4ms | 48.85
| PostStore.SetPostReminder | avg | 25ms | 37ms | 12ms | 48.14
| PreferenceStore.DeleteCategoryAndName | avg | 12ms | 17ms | 5ms | 41.53
| PostStore.GetPostReminderMetadata | avg | 8ms | 11ms | 3ms | 37.04
| JobStore.GetCountByStatusAndType | avg | 9ms | 12ms | 3ms | 32.22
| PostStore.AnalyticsPostCount | avg | 491ms | 649ms | 158ms | 32.15
| UserStore.Update | avg | 24ms | 31ms | 7ms | 29.73
| PostStore.GetPostReminders | avg | 20ms | 26ms | 6ms | 29.70
| StatusStore.Get | avg | 7ms | 9ms | 2ms | 29.11
| JobStore.UpdateStatus | avg | 8ms | 10ms | 2ms | 24.25
| PostStore.GetPostsAfter | avg | 10ms | 12ms | 2ms | 19.99
| UserStore.GetMany | avg | 10ms | 12ms | 2ms | 19.99
| ChannelStore.GetChannelUnread | avg | 11ms | 13ms | 2ms | 17.59
| FileInfoStore.SetContent | avg | 23ms | 27ms | 4ms | 17.56
| DraftStore.Delete | avg | 12ms | 14ms | 2ms | 16.28
| PreferenceStore.Get | avg | 12ms | 14ms | 2ms | 16.28
| UserStore.GetByUsername | avg | 12ms | 14ms | 2ms | 16.07
| ChannelStore.GetChannels | avg | 12ms | 14ms | 2ms | 16.05
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 31ms | 36ms | 5ms | 15.92
| StatusStore.GetByIds | avg | 14ms | 16ms | 2ms | 14.41
| FileInfoStore.Save | avg | 14ms | 16ms | 2ms | 14.37
| PostStore.GetPostsBefore | avg | 14ms | 16ms | 2ms | 14.04
| DraftStore.Get | avg | 14ms | 16ms | 2ms | 14.01
| PostAcknowledgementStore.GetForPosts | avg | 14ms | 16ms | 2ms | 14.01
| WebhookStore.GetOutgoingByTeam | avg | 14ms | 16ms | 2ms | 13.91
| ThreadStore.GetThreadUnreadReplyCount | avg | 17ms | 19ms | 2ms | 11.45
| ChannelStore.AutocompleteInTeamForSearch | avg | 90ms | 100ms | 10ms | 11.12
| ThreadStore.GetThreadForUser | avg | 19ms | 21ms | 2ms | 10.27
| ChannelStore.GetPublicChannelsForTeam | avg | 31ms | 34ms | 3ms | 9.62
| ChannelStore.GetAllChannelMemberIdsByChannelId | avg | 31ms | 34ms | 3ms | 9.57
| UserStore.AutocompleteUsersInChannel | avg | 76ms | 83ms | 7ms | 9.26
| PostStore.Get | avg | 26ms | 28ms | 2ms | 7.79
| PostStore.GetPostsSince | avg | 28ms | 30ms | 2ms | 7.10
| TeamStore.SaveMember | avg | 48ms | 51ms | 3ms | 6.28
| ChannelStore.GetMemberCount | avg | 37ms | 39ms | 2ms | 5.46
| UserStore.Search | avg | 55ms | 58ms | 3ms | 5.45
| PostStore.Save | avg | 38ms | 40ms | 2ms | 5.32
| ChannelStore.CreateDirectChannel | avg | 78ms | 82ms | 4ms | 5.15
| PostStore.SearchPostsForUser | avg | 269ms | 278ms | 9ms | 3.34
| UserStore.Save | avg | 87ms | 89ms | 2ms | 2.30
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| JobStore.UpdateStatusOptimistically | p99 | 57ms | 188ms | 131ms | 227.83
| RoleStore.GetByNames | p99 | 76ms | 223ms | 147ms | 194.70
| JobStore.UpdateOptimistically | p99 | 43ms | 125ms | 82ms | 190.33
| UserStore.Count | p99 | 95ms | 223ms | 128ms | 134.03
| JobStore.UpdateStatus | p99 | 58ms | 125ms | 67ms | 114.53
| PostStore.SetPostReminder | p99 | 205ms | 430ms | 225ms | 109.76
| StatusStore.SaveOrUpdate | p99 | 224ms | 469ms | 245ms | 109.33
| PostStore.GetPostReminders | p99 | 205ms | 423ms | 218ms | 106.34
| ChannelStore.CreateSidebarCategory | p99 | 239ms | 493ms | 254ms | 106.06
| JobStore.GetCountByStatusAndType | p99 | 91ms | 186ms | 95ms | 103.94
| PostPersistentNotificationStore.Get | p99 | 37ms | 74ms | 37ms | 99.33
| ProductNoticesStore.ClearOldNotices | p99 | 50ms | 99ms | 49ms | 98.97
| BotStore.Get | p99 | 43ms | 85ms | 42ms | 98.82
| EmojiStore.GetMultipleByName | p99 | 25ms | 49ms | 24ms | 97.76
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 25ms | 49ms | 24ms | 97.08
| RoleStore.ChannelHigherScopedPermissions | p99 | 50ms | 98ms | 48ms | 95.05
| UserStore.GetProfilesNotInChannel | p99 | 25ms | 45ms | 20ms | 81.33
| PostStore.Delete | p99 | 240ms | 435ms | 195ms | 81.17
| UserAccessTokenStore.GetByToken | p99 | 49ms | 89ms | 40ms | 80.99
| FileInfoStore.Save | p99 | 118ms | 179ms | 61ms | 51.59
| ChannelStore.GetPinnedPostCount | p99 | 100ms | 142ms | 42ms | 42.06
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 314ms | 431ms | 117ms | 37.27
| ChannelStore.UpdateSidebarChannelsByPreferences | p99 | 93ms | 127ms | 34ms | 36.75
| FileInfoStore.GetForPost | p99 | 114ms | 154ms | 40ms | 35.20
| PostStore.GetPostsAfter | p99 | 87ms | 117ms | 30ms | 34.41
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | p99 | 105ms | 137ms | 32ms | 30.62
| LinkMetadataStore.Get | p99 | 98ms | 128ms | 30ms | 30.59
| JobStore.Get | p99 | 45ms | 58ms | 13ms | 29.01
| ClusterDiscoveryStore.SetLastPingAt | p99 | 132ms | 169ms | 37ms | 28.14
| EmojiStore.GetByName | p99 | 96ms | 121ms | 25ms | 26.03
| PostStore.GetSingle | p99 | 97ms | 120ms | 23ms | 23.61
| PostPersistentNotificationStore.DeleteExpired | p99 | 74ms | 91ms | 17ms | 22.82
| GroupStore.GetGroups | p99 | 99ms | 121ms | 22ms | 22.20
| ThreadStore.GetMembershipForUser | p99 | 98ms | 119ms | 21ms | 21.35
| TeamStore.SaveMember | p99 | 252ms | 304ms | 52ms | 20.63
| PostStore.GetEtag | p99 | 137ms | 165ms | 28ms | 20.48
| ChannelStore.GetPublicChannelsForTeam | p99 | 191ms | 229ms | 38ms | 19.91
| UserStore.GetProfilesByUsernames | p99 | 145ms | 171ms | 26ms | 17.92
| ChannelStore.SearchGroupChannels | p99 | 163ms | 192ms | 29ms | 17.82
| ChannelStore.GetChannelUnread | p99 | 126ms | 148ms | 22ms | 17.45
| PostStore.SearchPostsForUser | p99 | 2.478s | 2.909s | 431ms | 17.39
| StatusStore.Get | p99 | 84ms | 98ms | 14ms | 16.58
| DraftStore.Delete | p99 | 118ms | 137ms | 19ms | 16.12
| PreferenceStore.Get | p99 | 143ms | 166ms | 23ms | 16.05
| ChannelStore.GetChannels | p99 | 144ms | 167ms | 23ms | 16.02
| ChannelStore.GetMembersForUser | p99 | 142ms | 164ms | 22ms | 15.50
| PostStore.GetPostsByThread | p99 | 109ms | 125ms | 16ms | 14.64
| FileInfoStore.Get | p99 | 143ms | 163ms | 20ms | 13.98
| ThreadStore.GetTeamsUnreadForUser | p99 | 160ms | 182ms | 22ms | 13.72
| ThreadStore.Get | p99 | 97ms | 110ms | 13ms | 13.47
| ThreadStore.GetThreadUnreadReplyCount | p99 | 136ms | 154ms | 18ms | 13.25
| UserStore.GetMany | p99 | 85ms | 95ms | 10ms | 11.76
| ThreadStore.GetThreadsForUser | p99 | 163ms | 182ms | 19ms | 11.66
| ReactionStore.GetForPost | p99 | 89ms | 99ms | 10ms | 11.25
| PostStore.GetPostsBefore | p99 | 156ms | 173ms | 17ms | 10.92
| StatusStore.UpdateExpiredDNDStatuses | p99 | 205ms | 227ms | 22ms | 10.73
| DraftStore.Upsert | p99 | 141ms | 156ms | 15ms | 10.64
| JobStore.GetAllByStatus | p99 | 174ms | 192ms | 18ms | 10.37
| UserStore.GetUnreadCount | p99 | 98ms | 108ms | 10ms | 10.25
| UserStore.Update | p99 | 231ms | 254ms | 23ms | 9.97
| UserStore.GetProfileByIds | p99 | 147ms | 161ms | 14ms | 9.55
| WebhookStore.GetOutgoingByTeam | p99 | 174ms | 190ms | 16ms | 9.22
| PostStore.GetPosts | p99 | 82ms | 89ms | 7ms | 8.50
| ChannelStore.GetMemberLastViewedAt | p99 | 84ms | 91ms | 7ms | 8.30
| ChannelStore.Get | p99 | 193ms | 209ms | 16ms | 8.28
| ChannelStore.GetByName | p99 | 97ms | 105ms | 8ms | 8.24
| PostStore.GetPostIdAfterTime | p99 | 74ms | 80ms | 6ms | 8.12
| DraftStore.Get | p99 | 177ms | 191ms | 14ms | 7.90
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 81ms | 87ms | 6ms | 7.37
| TeamStore.Get | p99 | 95ms | 102ms | 7ms | 7.36
| PostAcknowledgementStore.GetForPosts | p99 | 198ms | 212ms | 14ms | 7.06
| PostPriorityStore.GetForPosts | p99 | 200ms | 213ms | 13ms | 6.50
| ThreadStore.GetThreadFollowers | p99 | 93ms | 99ms | 6ms | 6.45
| UserStore.AutocompleteUsersInChannel | p99 | 373ms | 397ms | 24ms | 6.44
| ChannelStore.GetMemberForPost | p99 | 178ms | 189ms | 11ms | 6.19
| FileInfoStore.SetContent | p99 | 217ms | 230ms | 13ms | 5.98
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 91ms | 96ms | 5ms | 5.52
| PostPersistentNotificationStore.GetSingle | p99 | 92ms | 97ms | 5ms | 5.42
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 95ms | 100ms | 5ms | 5.25
| ThreadStore.GetThreadForUser | p99 | 208ms | 218ms | 10ms | 4.81
| UserStore.IsEmpty | p99 | 43ms | 45ms | 2ms | 4.69
| ThreadStore.GetTotalThreads | p99 | 95ms | 99ms | 4ms | 4.23
| ThreadStore.GetTotalUnreadThreads | p99 | 95ms | 99ms | 4ms | 4.23
| ChannelStore.GetGuestCount | p99 | 96ms | 100ms | 4ms | 4.16
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 74ms | 77ms | 3ms | 4.05
| PostStore.Save | p99 | 383ms | 398ms | 15ms | 3.91
| UserStore.Save | p99 | 365ms | 379ms | 14ms | 3.84
| ChannelStore.GetMemberCount | p99 | 210ms | 218ms | 8ms | 3.81
| SessionStore.GetLRUSessions | p99 | 84ms | 87ms | 3ms | 3.58
| FileInfoStore.AttachToPost | p99 | 208ms | 215ms | 7ms | 3.37
| UserStore.GetForLogin | p99 | 90ms | 93ms | 3ms | 3.33
| PostStore.GetPostsSince | p99 | 217ms | 224ms | 7ms | 3.23
| TeamStore.GetTeamsForUser | p99 | 93ms | 96ms | 3ms | 3.21
| ThreadStore.GetTotalUnreadMentions | p99 | 96ms | 99ms | 3ms | 3.13
| PostStore.GetPostIdBeforeTime | p99 | 96ms | 99ms | 3ms | 3.12
| PluginStore.SetWithOptions | p99 | 144ms | 148ms | 4ms | 2.77
| UserStore.UpdateUpdateAt | p99 | 76ms | 78ms | 2ms | 2.64
| AuditStore.Save | p99 | 88ms | 90ms | 2ms | 2.28
| GroupStore.GetByName | p99 | 88ms | 90ms | 2ms | 2.27
| UserTermsOfServiceStore.GetByUser | p99 | 89ms | 91ms | 2ms | 2.24
| SessionStore.UpdateLastActivityAt | p99 | 94ms | 96ms | 2ms | 2.13
| UserStore.Get | p99 | 95ms | 97ms | 2ms | 2.11
| ChannelStore.IncrementMentionCount | p99 | 95ms | 97ms | 2ms | 2.10
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 96ms | 98ms | 2ms | 2.07
| ChannelStore.UpdateLastViewedAt | p99 | 97ms | 99ms | 2ms | 2.07
| ChannelStore.GetFileCount | p99 | 112ms | 114ms | 2ms | 1.79
| ThreadStore.MaintainMembership | p99 | 230ms | 234ms | 4ms | 1.74
| UserStore.Search | p99 | 236ms | 239ms | 3ms | 1.27
| PostStore.Get | p99 | 236ms | 239ms | 3ms | 1.27
| UserStore.GetByUsername | p99 | 170ms | 172ms | 2ms | 1.18
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| BotStore.Save | avg | 4ms | 0s | -4ms | -111.56
| ThreadStore.MarkAllAsReadByTeam | avg | 2ms | 0s | -2ms | -102.51
| CommandWebhookStore.Cleanup | avg | 19ms | 3ms | -16ms | -82.82
| TokenStore.Cleanup | avg | 13ms | 3ms | -10ms | -77.57
| ChannelStore.GetTeamChannels | avg | 51ms | 29ms | -22ms | -43.36
| ChannelStore.UpdateSidebarCategories | avg | 203ms | 117ms | -86ms | -42.47
| ChannelStore.GetSidebarCategory | avg | 44ms | 26ms | -18ms | -40.47
| UserStore.GetProfilesInChannel | avg | 10ms | 6ms | -4ms | -38.50
| SessionStore.GetSessionsExpired | avg | 8ms | 5ms | -3ms | -35.61
| ChannelStore.GetSidebarCategoriesForTeamForUser | avg | 44ms | 32ms | -12ms | -27.32
| ChannelStore.CreateInitialSidebarCategories | avg | 68ms | 50ms | -18ms | -26.64
| SessionStore.Remove | avg | 12ms | 9ms | -3ms | -24.22
| JobStore.Save | avg | 9ms | 7ms | -2ms | -22.59
| JobStore.UpdateStatusOptimistically | avg | 11ms | 9ms | -2ms | -18.40
| ChannelStore.GetMember | avg | 12ms | 10ms | -2ms | -17.03
| FileInfoStore.GetByIds | avg | 13ms | 11ms | -2ms | -15.04
| TeamStore.GetTotalMemberCount | avg | 82ms | 70ms | -12ms | -14.71
| PostStore.Update | avg | 42ms | 36ms | -6ms | -14.46
| TeamStore.GetActiveMemberCount | avg | 91ms | 78ms | -13ms | -14.27
| ChannelStore.SearchGroupChannels | avg | 19ms | 17ms | -2ms | -10.40
| UserStore.Count | avg | 27ms | 25ms | -2ms | -7.30
| ChannelStore.Save | avg | 51ms | 49ms | -2ms | -3.91
| UserStore.GetAllProfilesInChannel | avg | 461ms | 450ms | -11ms | -2.39
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| BotStore.Save | p99 | 5ms | 0s | -5ms | -101.01
| ThreadStore.MarkAllAsReadByTeam | p99 | 5ms | 0s | -5ms | -101.01
| CommandWebhookStore.Cleanup | p99 | 49ms | 5ms | -44ms | -89.80
| ChannelStore.GetTeamChannels | p99 | 472ms | 97ms | -375ms | -79.37
| ChannelStore.AutocompleteInTeamForSearch | p99 | 1.945s | 481ms | -1.464s | -75.27
| TokenStore.Cleanup | p99 | 25ms | 10ms | -15ms | -60.73
| ChannelStore.UpdateSidebarCategories | p99 | 1.78s | 818ms | -962ms | -54.04
| SessionStore.GetSessionsExpired | p99 | 49ms | 24ms | -25ms | -51.55
| FileInfoStore.GetByIds | p99 | 182ms | 98ms | -84ms | -46.06
| ChannelStore.CreateDirectChannel | p99 | 759ms | 463ms | -296ms | -39.00
| PostStore.Update | p99 | 368ms | 229ms | -139ms | -37.82
| PostStore.GetPostReminderMetadata | p99 | 70ms | 48ms | -22ms | -31.43
| JobStore.Save | p99 | 58ms | 46ms | -12ms | -20.69
| ThreadStore.MarkAllAsReadByChannels | p99 | 126ms | 100ms | -26ms | -20.63
| ChannelStore.GetSidebarCategory | p99 | 260ms | 213ms | -47ms | -18.08
| ChannelStore.Save | p99 | 429ms | 368ms | -61ms | -14.21
| ChannelStore.GetMember | p99 | 114ms | 98ms | -16ms | -13.99
| SessionStore.Remove | p99 | 205ms | 179ms | -26ms | -12.68
| PreferenceStore.DeleteCategoryAndName | p99 | 94ms | 87ms | -7ms | -7.49
| ChannelStore.GetAllChannelMemberIdsByChannelId | p99 | 233ms | 216ms | -17ms | -7.29
| PostAcknowledgementStore.GetForPost | p99 | 89ms | 83ms | -6ms | -6.78
| StatusStore.GetByIds | p99 | 208ms | 194ms | -14ms | -6.73
| ProductNoticesStore.View | p99 | 690ms | 648ms | -42ms | -6.09
| SessionStore.Save | p99 | 177ms | 168ms | -9ms | -5.09
| PluginStore.Delete | p99 | 72ms | 70ms | -2ms | -2.76
| UserStore.UpdateLastLogin | p99 | 80ms | 78ms | -2ms | -2.50
| PostPriorityStore.GetForPost | p99 | 88ms | 86ms | -2ms | -2.26
| TeamStore.GetActiveMemberCount | p99 | 245ms | 240ms | -5ms | -2.04
| UserStore.GetAllProfilesInChannel | p99 | 2.295s | 2.258s | -37ms | -1.61
| ChannelStore.SaveMember | p99 | 488ms | 481ms | -7ms | -1.43
| SessionStore.Get | p99 | 214ms | 211ms | -3ms | -1.40
| ChannelStore.CreateInitialSidebarCategories | p99 | 471ms | 466ms | -5ms | -1.06
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| createCategoryForTeamForUser | avg | 47ms | 213ms | 166ms | 351.57
| deletePost | avg | 76ms | 137ms | 61ms | 79.82
| setPostReminder | avg | 60ms | 99ms | 39ms | 64.54
| getUsersByNames | avg | 13ms | 15ms | 2ms | 14.98
| deleteDraft | avg | 15ms | 17ms | 2ms | 13.01
| autocompleteChannelsForTeamForSearch | avg | 90ms | 100ms | 10ms | 11.09
| getPostsForChannel | avg | 114ms | 126ms | 12ms | 10.52
| autocompleteUsers | avg | 69ms | 76ms | 7ms | 10.08
| updatePreferences | avg | 43ms | 47ms | 4ms | 9.36
| removeUserCustomStatus | avg | 405ms | 435ms | 30ms | 7.41
| updateReadStateThreadByUser | avg | 147ms | 157ms | 10ms | 6.82
| createPost | avg | 895ms | 953ms | 58ms | 6.48
| viewChannel | avg | 47ms | 50ms | 3ms | 6.43
| getPostThread | avg | 64ms | 68ms | 4ms | 6.23
| getPublicChannelsForTeam | avg | 34ms | 36ms | 2ms | 5.91
| searchUsers | avg | 58ms | 61ms | 3ms | 5.17
| saveReaction | avg | 41ms | 43ms | 2ms | 4.93
| searchPostsInTeam | avg | 295ms | 309ms | 14ms | 4.74
| getFileThumbnail | avg | 58ms | 60ms | 2ms | 3.46
| uploadFileStream | avg | 492ms | 508ms | 16ms | 3.25
| getFilePreview | avg | 75ms | 77ms | 2ms | 2.68
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| createCategoryForTeamForUser | p99 | 239ms | 493ms | 254ms | 106.06
| setPostReminder | p99 | 425ms | 860ms | 435ms | 102.35
| deletePost | p99 | 468ms | 870ms | 402ms | 85.99
| searchPostsInTeam | p99 | 2.62s | 3.606s | 986ms | 37.64
| getUserStatusesByIds | p99 | 46ms | 55ms | 9ms | 19.38
| getPostsForChannel | p99 | 1.294s | 1.506s | 212ms | 16.39
| getUsersByNames | p99 | 163ms | 179ms | 16ms | 9.82
| searchGroupChannels | p99 | 178ms | 194ms | 16ms | 9.01
| getChannelStats | p99 | 123ms | 134ms | 11ms | 8.94
| getChannelUnread | p99 | 160ms | 174ms | 14ms | 8.73
| autocompleteUsers | p99 | 356ms | 379ms | 23ms | 6.47
| getTeamMembersForUser | p99 | 152ms | 160ms | 8ms | 5.26
| updatePreferences | p99 | 391ms | 411ms | 20ms | 5.11
| getFileThumbnail | p99 | 344ms | 359ms | 15ms | 4.36
| getThreadsForUser | p99 | 185ms | 193ms | 8ms | 4.32
| deleteDraft | p99 | 192ms | 199ms | 7ms | 3.64
| getChannelMembersForTeamForUser | p99 | 165ms | 171ms | 6ms | 3.64
| getPublicChannelsForTeam | p99 | 221ms | 229ms | 8ms | 3.62
| updateReadStateThreadByUser | p99 | 925ms | 955ms | 30ms | 3.24
| viewChannel | p99 | 444ms | 458ms | 14ms | 3.15
| getChannelsForUser | p99 | 103ms | 106ms | 3ms | 2.93
| getFilePreview | p99 | 410ms | 421ms | 11ms | 2.68
| getPostsForChannelAroundLastUnread | p99 | 472ms | 483ms | 11ms | 2.33
| removeUserCustomStatus | p99 | 2.194s | 2.233s | 39ms | 1.78
| saveReaction | p99 | 356ms | 362ms | 6ms | 1.68
| getPostThread | p99 | 492ms | 500ms | 8ms | 1.63
| uploadFileStream | p99 | 2.229s | 2.263s | 34ms | 1.53
| createPost | p99 | 4.787s | 4.858s | 71ms | 1.48
| getDrafts | p99 | 181ms | 183ms | 2ms | 1.11
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| updateReadStateAllThreadsByUser | avg | 2ms | 0s | -2ms | -97.65
| updateCategoriesForTeamForUser | avg | 306ms | 179ms | -127ms | -41.51
| createChannel | avg | 808ms | 501ms | -307ms | -37.99
| getTeamStats | avg | 123ms | 79ms | -44ms | -35.64
| createDirectChannel | avg | 777ms | 554ms | -223ms | -28.69
| createGroupChannel | avg | 1.28s | 925ms | -355ms | -27.72
| getCategoriesForTeamForUser | avg | 45ms | 33ms | -12ms | -26.89
| getChannel | avg | 32ms | 24ms | -8ms | -24.82
| unfollowThreadByUser | avg | 69ms | 55ms | -14ms | -20.35
| login | avg | 234ms | 194ms | -40ms | -17.11
| createUser | avg | 335ms | 280ms | -55ms | -16.41
| searchGroupChannels | avg | 20ms | 17ms | -3ms | -15.13
| patchPost | avg | 131ms | 112ms | -19ms | -14.48
| getUsers | avg | 16ms | 14ms | -2ms | -12.74
| addChannelMember | avg | 626ms | 557ms | -69ms | -11.03
| followThreadByUser | avg | 51ms | 46ms | -5ms | -9.89
| getProfileImage | avg | 86ms | 80ms | -6ms | -7.02
| logout | avg | 201ms | 190ms | -11ms | -5.48
| addTeamMember | avg | 1.518s | 1.472s | -46ms | -3.03
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| updateReadStateAllThreadsByUser | p99 | 5ms | 0s | -5ms | -101.01
| autocompleteChannelsForTeamForSearch | p99 | 1.945s | 620ms | -1.325s | -68.12
| logout | p99 | 2.05s | 883ms | -1.167s | -56.93
| updateCategoriesForTeamForUser | p99 | 2.14s | 939ms | -1.201s | -56.12
| patchPost | p99 | 990ms | 490ms | -500ms | -50.51
| getTeamStats | p99 | 472ms | 244ms | -228ms | -48.25
| createGroupChannel | p99 | 7.5s | 4.409s | -3.091s | -41.21
| createDirectChannel | p99 | 4.031s | 2.406s | -1.625s | -40.31
| getChannel | p99 | 307ms | 207ms | -100ms | -32.59
| getAllTeams | p99 | 154ms | 133ms | -21ms | -13.64
| login | p99 | 2.139s | 1.86s | -279ms | -13.04
| createUser | p99 | 2.233s | 1.957s | -276ms | -12.36
| addChannelMember | p99 | 2.95s | 2.625s | -325ms | -11.02
| getPreferences | p99 | 134ms | 121ms | -13ms | -9.71
| getTeamMember | p99 | 199ms | 180ms | -19ms | -9.55
| getTeamsForUser | p99 | 105ms | 97ms | -8ms | -7.64
| getChannelMember | p99 | 249ms | 236ms | -13ms | -5.22
| getUser | p99 | 240ms | 229ms | -11ms | -4.59
| getUsers | p99 | 231ms | 222ms | -9ms | -3.90
| createChannel | p99 | 2.417s | 2.35s | -67ms | -2.77
| addTeamMember | p99 | 8.392s | 8.165s | -227ms | -2.70
| getClientConfig | p99 | 246ms | 240ms | -6ms | -2.44
| getCategoriesForTeamForUser | p99 | 241ms | 238ms | -3ms | -1.25
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 88ms| 90ms | 2ms | 2.279
| BotStore.Get |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 43ms| 85ms | 42ms | 98.824
| BotStore.Save |  Avg| 4ms| 0s | -4ms | -111.562
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 74ms| 77ms | 3ms | 4.055
| ChannelStore.Autocomplete |  Avg| 61ms| 61ms | 0s | 0.000
| |  P99| 241ms| 240ms | -1ms | -0.414
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 90ms| 100ms | 10ms | 11.116
| |  P99| 1.945s| 481ms | -1.464s | -75.270
| ChannelStore.CreateDirectChannel |  Avg| 78ms| 82ms | 4ms | 5.151
| |  P99| 759ms| 463ms | -296ms | -38.999
| ChannelStore.CreateInitialSidebarCategories |  Avg| 68ms| 50ms | -18ms | -26.642
| |  P99| 471ms| 466ms | -5ms | -1.062
| ChannelStore.CreateSidebarCategory |  Avg| 43ms| 177ms | 134ms | 312.114
| |  P99| 239ms| 493ms | 254ms | 106.055
| ChannelStore.Get |  Avg| 18ms| 19ms | 1ms | 5.678
| |  P99| 193ms| 209ms | 16ms | 8.277
| ChannelStore.GetAllChannelMemberIdsByChannelId |  Avg| 31ms| 34ms | 3ms | 9.570
| |  P99| 233ms| 216ms | -17ms | -7.292
| ChannelStore.GetAllChannelMembersForUser |  Avg| 12ms| 13ms | 1ms | 8.189
| |  P99| 97ms| 98ms | 1ms | 1.036
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 31ms| 36ms | 5ms | 15.923
| |  P99| 314ms| 431ms | 117ms | 37.270
| ChannelStore.GetByName |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 97ms| 105ms | 8ms | 8.240
| ChannelStore.GetChannelUnread |  Avg| 11ms| 13ms | 2ms | 17.586
| |  P99| 126ms| 148ms | 22ms | 17.448
| ChannelStore.GetChannels |  Avg| 12ms| 14ms | 2ms | 16.047
| |  P99| 144ms| 167ms | 23ms | 16.015
| ChannelStore.GetChannelsByUser |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 100ms| 99ms | -1ms | -1.003
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 11ms| 12ms | 1ms | 9.194
| |  P99| 105ms| 137ms | 32ms | 30.621
| ChannelStore.GetFileCount |  Avg| 13ms| 14ms | 1ms | 7.712
| |  P99| 112ms| 114ms | 2ms | 1.789
| ChannelStore.GetGuestCount |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 96ms| 100ms | 4ms | 4.159
| ChannelStore.GetMember |  Avg| 12ms| 10ms | -2ms | -17.032
| |  P99| 114ms| 98ms | -16ms | -13.988
| ChannelStore.GetMemberCount |  Avg| 37ms| 39ms | 2ms | 5.458
| |  P99| 210ms| 218ms | 8ms | 3.806
| ChannelStore.GetMemberForPost |  Avg| 18ms| 19ms | 1ms | 5.642
| |  P99| 178ms| 189ms | 11ms | 6.189
| ChannelStore.GetMemberLastViewedAt |  Avg| 7ms| 8ms | 1ms | 14.079
| |  P99| 84ms| 91ms | 7ms | 8.305
| ChannelStore.GetMembersForUser |  Avg| 13ms| 14ms | 1ms | 7.654
| |  P99| 142ms| 164ms | 22ms | 15.499
| ChannelStore.GetPinnedPostCount |  Avg| 11ms| 12ms | 1ms | 9.091
| |  P99| 100ms| 142ms | 42ms | 42.063
| ChannelStore.GetPublicChannelsForTeam |  Avg| 31ms| 34ms | 3ms | 9.623
| |  P99| 191ms| 229ms | 38ms | 19.906
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 44ms| 32ms | -12ms | -27.323
| |  P99| 238ms| 236ms | -2ms | -0.839
| ChannelStore.GetSidebarCategory |  Avg| 44ms| 26ms | -18ms | -40.471
| |  P99| 260ms| 213ms | -47ms | -18.077
| ChannelStore.GetTeamChannels |  Avg| 51ms| 29ms | -22ms | -43.362
| |  P99| 472ms| 97ms | -375ms | -79.365
| ChannelStore.IncrementMentionCount |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 95ms| 97ms | 2ms | 2.099
| ChannelStore.Save |  Avg| 51ms| 49ms | -2ms | -3.913
| |  P99| 429ms| 368ms | -61ms | -14.207
| ChannelStore.SaveMember |  Avg| 65ms| 66ms | 1ms | 1.529
| |  P99| 488ms| 481ms | -7ms | -1.435
| ChannelStore.SearchGroupChannels |  Avg| 19ms| 17ms | -2ms | -10.396
| |  P99| 163ms| 192ms | 29ms | 17.825
| ChannelStore.UpdateLastViewedAt |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 97ms| 99ms | 2ms | 2.070
| ChannelStore.UpdateSidebarCategories |  Avg| 203ms| 117ms | -86ms | -42.467
| |  P99| 1.78s| 818ms | -962ms | -54.045
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 9ms| 10ms | 1ms | 11.030
| |  P99| 93ms| 127ms | 34ms | 36.750
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 132ms| 169ms | 37ms | 28.137
| CommandWebhookStore.Cleanup |  Avg| 19ms| 3ms | -16ms | -82.819
| |  P99| 49ms| 5ms | -44ms | -89.796
| DesktopTokensStore.DeleteOlderThan |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Delete |  Avg| 12ms| 14ms | 2ms | 16.284
| |  P99| 118ms| 137ms | 19ms | 16.121
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 12ms| 18ms | 6ms | 49.716
| |  P99| 25ms| 49ms | 24ms | 97.082
| DraftStore.Get |  Avg| 14ms| 16ms | 2ms | 14.014
| |  P99| 177ms| 191ms | 14ms | 7.901
| DraftStore.GetDraftsForUser |  Avg| 14ms| 15ms | 1ms | 7.333
| |  P99| 168ms| 168ms | 0s | 0.000
| DraftStore.Upsert |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 141ms| 156ms | 15ms | 10.636
| EmojiStore.GetByName |  Avg| 10ms| 11ms | 1ms | 9.851
| |  P99| 96ms| 121ms | 25ms | 26.032
| EmojiStore.GetMultipleByName |  Avg| 8ms| 12ms | 4ms | 48.849
| |  P99| 25ms| 49ms | 24ms | 97.760
| FileInfoStore.AttachToPost |  Avg| 20ms| 21ms | 1ms | 4.991
| |  P99| 208ms| 215ms | 7ms | 3.367
| FileInfoStore.Get |  Avg| 12ms| 13ms | 1ms | 8.426
| |  P99| 143ms| 163ms | 20ms | 13.980
| FileInfoStore.GetByIds |  Avg| 13ms| 11ms | -2ms | -15.045
| |  P99| 182ms| 98ms | -84ms | -46.062
| FileInfoStore.GetForPost |  Avg| 11ms| 12ms | 1ms | 8.935
| |  P99| 114ms| 154ms | 40ms | 35.200
| FileInfoStore.Save |  Avg| 14ms| 16ms | 2ms | 14.366
| |  P99| 118ms| 179ms | 61ms | 51.586
| FileInfoStore.SetContent |  Avg| 23ms| 27ms | 4ms | 17.557
| |  P99| 217ms| 230ms | 13ms | 5.982
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 81ms| 87ms | 6ms | 7.370
| GroupStore.GetByName |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 88ms| 90ms | 2ms | 2.275
| GroupStore.GetGroups |  Avg| 11ms| 12ms | 1ms | 9.022
| |  P99| 99ms| 121ms | 22ms | 22.203
| JobStore.Get |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 45ms| 58ms | 13ms | 29.010
| JobStore.GetAllByStatus |  Avg| 14ms| 15ms | 1ms | 7.337
| |  P99| 174ms| 192ms | 18ms | 10.371
| JobStore.GetCountByStatusAndType |  Avg| 9ms| 12ms | 3ms | 32.219
| |  P99| 91ms| 186ms | 95ms | 103.939
| JobStore.GetNewestJobByStatusesAndType |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 121ms| 121ms | 0s | 0.000
| JobStore.Save |  Avg| 9ms| 7ms | -2ms | -22.588
| |  P99| 58ms| 46ms | -12ms | -20.690
| JobStore.UpdateOptimistically |  Avg| 7ms| 8ms | 1ms | 14.729
| |  P99| 43ms| 125ms | 82ms | 190.329
| JobStore.UpdateStatus |  Avg| 8ms| 10ms | 2ms | 24.245
| |  P99| 58ms| 125ms | 67ms | 114.530
| JobStore.UpdateStatusOptimistically |  Avg| 11ms| 9ms | -2ms | -18.398
| |  P99| 57ms| 188ms | 131ms | 227.827
| LinkMetadataStore.Get |  Avg| 10ms| 11ms | 1ms | 9.913
| |  P99| 98ms| 128ms | 30ms | 30.595
| LinkMetadataStore.Save |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 41ms| 42ms | 1ms | 2.410
| PluginStore.Delete |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 72ms| 70ms | -2ms | -2.762
| PluginStore.List |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 204ms| 204ms | 0s | 0.000
| PluginStore.SetWithOptions |  Avg| 13ms| 12ms | -1ms | -7.987
| |  P99| 144ms| 148ms | 4ms | 2.771
| PostAcknowledgementStore.GetForPost |  Avg| 9ms| 8ms | -1ms | -11.569
| |  P99| 89ms| 83ms | -6ms | -6.780
| PostAcknowledgementStore.GetForPosts |  Avg| 14ms| 16ms | 2ms | 14.011
| |  P99| 198ms| 212ms | 14ms | 7.065
| PostPersistentNotificationStore.DeleteExpired |  Avg| 6ms| 7ms | 1ms | 17.221
| |  P99| 74ms| 91ms | 17ms | 22.819
| PostPersistentNotificationStore.Get |  Avg| 5ms| 8ms | 3ms | 65.489
| |  P99| 37ms| 74ms | 37ms | 99.330
| PostPersistentNotificationStore.GetSingle |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 92ms| 97ms | 5ms | 5.423
| PostPriorityStore.GetForPost |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 88ms| 86ms | -2ms | -2.260
| PostPriorityStore.GetForPosts |  Avg| 15ms| 16ms | 1ms | 6.787
| |  P99| 200ms| 213ms | 13ms | 6.500
| PostStore.AnalyticsPostCount |  Avg| 491ms| 649ms | 158ms | 32.150
| |  P99| 990ms| 995ms | 5ms | 0.505
| PostStore.Delete |  Avg| 40ms| 84ms | 44ms | 108.797
| |  P99| 240ms| 435ms | 195ms | 81.166
| PostStore.Get |  Avg| 26ms| 28ms | 2ms | 7.786
| |  P99| 236ms| 239ms | 3ms | 1.270
| PostStore.GetEtag |  Avg| 12ms| 13ms | 1ms | 8.370
| |  P99| 137ms| 165ms | 28ms | 20.479
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 6ms| 7ms | 1ms | 16.118
| |  P99| 74ms| 80ms | 6ms | 8.116
| PostStore.GetPostIdBeforeTime |  Avg| 9ms| 10ms | 1ms | 10.572
| |  P99| 96ms| 99ms | 3ms | 3.118
| PostStore.GetPostReminderMetadata |  Avg| 8ms| 11ms | 3ms | 37.040
| |  P99| 70ms| 48ms | -22ms | -31.429
| PostStore.GetPostReminders |  Avg| 20ms| 26ms | 6ms | 29.697
| |  P99| 205ms| 423ms | 218ms | 106.341
| PostStore.GetPosts |  Avg| 8ms| 9ms | 1ms | 11.827
| |  P99| 82ms| 89ms | 7ms | 8.504
| PostStore.GetPostsAfter |  Avg| 10ms| 12ms | 2ms | 19.993
| |  P99| 87ms| 117ms | 30ms | 34.414
| PostStore.GetPostsBefore |  Avg| 14ms| 16ms | 2ms | 14.038
| |  P99| 156ms| 173ms | 17ms | 10.922
| PostStore.GetPostsByThread |  Avg| 16ms| 17ms | 1ms | 6.290
| |  P99| 109ms| 125ms | 16ms | 14.637
| PostStore.GetPostsSince |  Avg| 28ms| 30ms | 2ms | 7.098
| |  P99| 217ms| 224ms | 7ms | 3.230
| PostStore.GetSingle |  Avg| 10ms| 11ms | 1ms | 9.990
| |  P99| 97ms| 120ms | 23ms | 23.614
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 38ms| 40ms | 2ms | 5.320
| |  P99| 383ms| 398ms | 15ms | 3.912
| PostStore.SearchPostsForUser |  Avg| 269ms| 278ms | 9ms | 3.341
| |  P99| 2.478s| 2.909s | 431ms | 17.393
| PostStore.SetPostReminder |  Avg| 25ms| 37ms | 12ms | 48.137
| |  P99| 205ms| 430ms | 225ms | 109.757
| PostStore.Update |  Avg| 42ms| 36ms | -6ms | -14.458
| |  P99| 368ms| 229ms | -139ms | -37.823
| PreferenceStore.DeleteCategoryAndName |  Avg| 12ms| 17ms | 5ms | 41.530
| |  P99| 94ms| 87ms | -7ms | -7.487
| PreferenceStore.Get |  Avg| 12ms| 14ms | 2ms | 16.280
| |  P99| 143ms| 166ms | 23ms | 16.055
| PreferenceStore.GetAll |  Avg| 10ms| 9ms | -1ms | -9.901
| |  P99| 99ms| 99ms | 0s | 0.000
| PreferenceStore.Save |  Avg| 26ms| 27ms | 1ms | 3.849
| |  P99| 242ms| 243ms | 1ms | 0.413
| ProductNoticesStore.ClearOldNotices |  Avg| 30ms| 60ms | 30ms | 101.086
| |  P99| 50ms| 99ms | 49ms | 98.966
| ProductNoticesStore.View |  Avg| 73ms| 73ms | 0s | 0.000
| |  P99| 690ms| 648ms | -42ms | -6.087
| ReactionStore.GetForPost |  Avg| 10ms| 9ms | -1ms | -10.419
| |  P99| 89ms| 99ms | 10ms | 11.251
| RoleStore.ChannelHigherScopedPermissions |  Avg| 9ms| 14ms | 5ms | 53.009
| |  P99| 50ms| 98ms | 48ms | 95.050
| RoleStore.GetByNames |  Avg| 12ms| 27ms | 15ms | 125.391
| |  P99| 76ms| 223ms | 147ms | 194.702
| SessionStore.Get |  Avg| 18ms| 17ms | -1ms | -5.489
| |  P99| 214ms| 211ms | -3ms | -1.402
| SessionStore.GetLRUSessions |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 84ms| 87ms | 3ms | 3.577
| SessionStore.GetSessionsExpired |  Avg| 8ms| 5ms | -3ms | -35.606
| |  P99| 49ms| 24ms | -25ms | -51.546
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 91ms| 96ms | 5ms | 5.518
| SessionStore.Remove |  Avg| 12ms| 9ms | -3ms | -24.218
| |  P99| 205ms| 179ms | -26ms | -12.683
| SessionStore.Save |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 177ms| 168ms | -9ms | -5.087
| SessionStore.UpdateLastActivityAt |  Avg| 11ms| 12ms | 1ms | 9.037
| |  P99| 94ms| 96ms | 2ms | 2.132
| StatusStore.Get |  Avg| 7ms| 9ms | 2ms | 29.106
| |  P99| 84ms| 98ms | 14ms | 16.578
| StatusStore.GetByIds |  Avg| 14ms| 16ms | 2ms | 14.407
| |  P99| 208ms| 194ms | -14ms | -6.731
| StatusStore.SaveOrUpdate |  Avg| 18ms| 28ms | 10ms | 56.125
| |  P99| 224ms| 469ms | 245ms | 109.325
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 13ms| 14ms | 1ms | 7.915
| |  P99| 205ms| 227ms | 22ms | 10.732
| StatusStore.UpdateLastActivityAt |  Avg| 10ms| 11ms | 1ms | 9.719
| |  P99| 95ms| 96ms | 1ms | 1.049
| SystemStore.GetByName |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 89ms| 88ms | -1ms | -1.130
| TeamStore.Get |  Avg| 9ms| 10ms | 1ms | 10.801
| |  P99| 95ms| 102ms | 7ms | 7.356
| TeamStore.GetActiveMemberCount |  Avg| 91ms| 78ms | -13ms | -14.274
| |  P99| 245ms| 240ms | -5ms | -2.045
| TeamStore.GetAllPage |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 95ms| 94ms | -1ms | -1.054
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 96ms| 98ms | 2ms | 2.073
| TeamStore.GetMember |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 49ms| 49ms | 0s | 0.000
| TeamStore.GetTeamsByUserId |  Avg| 9ms| 8ms | -1ms | -11.582
| |  P99| 97ms| 96ms | -1ms | -1.030
| TeamStore.GetTeamsForUser |  Avg| 8ms| 9ms | 1ms | 11.814
| |  P99| 93ms| 96ms | 3ms | 3.212
| TeamStore.GetTotalMemberCount |  Avg| 82ms| 70ms | -12ms | -14.705
| |  P99| 233ms| 235ms | 2ms | 0.857
| TeamStore.SaveMember |  Avg| 48ms| 51ms | 3ms | 6.275
| |  P99| 252ms| 304ms | 52ms | 20.628
| ThreadStore.Get |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 97ms| 110ms | 13ms | 13.472
| ThreadStore.GetMembershipForUser |  Avg| 10ms| 11ms | 1ms | 9.898
| |  P99| 98ms| 119ms | 21ms | 21.355
| ThreadStore.GetTeamsUnreadForUser |  Avg| 13ms| 14ms | 1ms | 7.986
| |  P99| 160ms| 182ms | 22ms | 13.723
| ThreadStore.GetThreadFollowers |  Avg| 10ms| 11ms | 1ms | 10.313
| |  P99| 93ms| 99ms | 6ms | 6.449
| ThreadStore.GetThreadForUser |  Avg| 19ms| 21ms | 2ms | 10.273
| |  P99| 208ms| 218ms | 10ms | 4.815
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 17ms| 19ms | 2ms | 11.454
| |  P99| 136ms| 154ms | 18ms | 13.252
| ThreadStore.GetThreadsForUser |  Avg| 15ms| 16ms | 1ms | 6.692
| |  P99| 163ms| 182ms | 19ms | 11.661
| ThreadStore.GetTotalThreads |  Avg| 9ms| 10ms | 1ms | 11.155
| |  P99| 95ms| 99ms | 4ms | 4.233
| ThreadStore.GetTotalUnreadMentions |  Avg| 9ms| 10ms | 1ms | 10.688
| |  P99| 96ms| 99ms | 3ms | 3.126
| ThreadStore.GetTotalUnreadThreads |  Avg| 9ms| 10ms | 1ms | 11.105
| |  P99| 95ms| 99ms | 4ms | 4.232
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 9ms| 10ms | 1ms | 10.733
| |  P99| 95ms| 100ms | 5ms | 5.248
| ThreadStore.MaintainMembership |  Avg| 22ms| 23ms | 1ms | 4.551
| |  P99| 230ms| 234ms | 4ms | 1.740
| ThreadStore.MarkAllAsReadByChannels |  Avg| 10ms| 11ms | 1ms | 9.570
| |  P99| 126ms| 100ms | -26ms | -20.632
| ThreadStore.MarkAllAsReadByTeam |  Avg| 2ms| 0s | -2ms | -102.515
| |  P99| 5ms| 0s | -5ms | -101.010
| ThreadStore.MarkAsRead |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 95ms| 95ms | 0s | 0.000
| ThreadStore.UpdateMembership |  Avg| 10ms| 11ms | 1ms | 9.746
| |  P99| 93ms| 94ms | 1ms | 1.077
| TokenStore.Cleanup |  Avg| 13ms| 3ms | -10ms | -77.572
| |  P99| 25ms| 10ms | -15ms | -60.729
| UserAccessTokenStore.GetByToken |  Avg| 8ms| 13ms | 5ms | 58.848
| |  P99| 49ms| 89ms | 40ms | 80.994
| UserStore.AutocompleteUsersInChannel |  Avg| 76ms| 83ms | 7ms | 9.264
| |  P99| 373ms| 397ms | 24ms | 6.440
| UserStore.Count |  Avg| 27ms| 25ms | -2ms | -7.300
| |  P99| 95ms| 223ms | 128ms | 134.031
| UserStore.Get |  Avg| 8ms| 9ms | 1ms | 12.181
| |  P99| 95ms| 97ms | 2ms | 2.106
| UserStore.GetAllProfiles |  Avg| 8ms| 7ms | -1ms | -13.307
| |  P99| 72ms| 73ms | 1ms | 1.388
| UserStore.GetAllProfilesInChannel |  Avg| 461ms| 450ms | -11ms | -2.387
| |  P99| 2.295s| 2.258s | -37ms | -1.613
| UserStore.GetByUsername |  Avg| 12ms| 14ms | 2ms | 16.071
| |  P99| 170ms| 172ms | 2ms | 1.176
| UserStore.GetForLogin |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 90ms| 93ms | 3ms | 3.334
| UserStore.GetMany |  Avg| 10ms| 12ms | 2ms | 19.989
| |  P99| 85ms| 95ms | 10ms | 11.765
| UserStore.GetProfileByIds |  Avg| 12ms| 13ms | 1ms | 8.051
| |  P99| 147ms| 161ms | 14ms | 9.548
| UserStore.GetProfilesByUsernames |  Avg| 13ms| 14ms | 1ms | 7.948
| |  P99| 145ms| 171ms | 26ms | 17.918
| UserStore.GetProfilesInChannel |  Avg| 10ms| 6ms | -4ms | -38.497
| |  P99| 25ms| 24ms | -1ms | -4.051
| UserStore.GetProfilesNotInChannel |  Avg| 11ms| 12ms | 1ms | 9.386
| |  P99| 25ms| 45ms | 20ms | 81.331
| UserStore.GetUnreadCount |  Avg| 10ms| 11ms | 1ms | 9.565
| |  P99| 98ms| 108ms | 10ms | 10.246
| UserStore.IsEmpty |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 43ms| 45ms | 2ms | 4.689
| UserStore.Save |  Avg| 87ms| 89ms | 2ms | 2.303
| |  P99| 365ms| 379ms | 14ms | 3.838
| UserStore.Search |  Avg| 55ms| 58ms | 3ms | 5.453
| |  P99| 236ms| 239ms | 3ms | 1.272
| UserStore.Update |  Avg| 24ms| 31ms | 7ms | 29.731
| |  P99| 231ms| 254ms | 23ms | 9.965
| UserStore.UpdateFailedPasswordAttempts |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 90ms| 91ms | 1ms | 1.107
| UserStore.UpdateLastLogin |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 80ms| 78ms | -2ms | -2.503
| UserStore.UpdateUpdateAt |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 76ms| 78ms | 2ms | 2.640
| UserTermsOfServiceStore.GetByUser |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 89ms| 91ms | 2ms | 2.244
| WebhookStore.GetOutgoingByTeam |  Avg| 14ms| 16ms | 2ms | 13.907
| |  P99| 174ms| 190ms | 16ms | 9.219
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 626ms| 557ms | -69ms | -11.026
| | P99| 2.95s| 2.625s | -325ms | -11.017
| addTeamMember | Avg| 1.518s| 1.472s | -46ms | -3.031
| | P99| 8.392s| 8.165s | -227ms | -2.705
| autocompleteChannelsForTeamForSearch | Avg| 90ms| 100ms | 10ms | 11.087
| | P99| 1.945s| 620ms | -1.325s | -68.123
| autocompleteUsers | Avg| 69ms| 76ms | 7ms | 10.078
| | P99| 356ms| 379ms | 23ms | 6.468
| createCategoryForTeamForUser | Avg| 47ms| 213ms | 166ms | 351.573
| | P99| 239ms| 493ms | 254ms | 106.055
| createChannel | Avg| 808ms| 501ms | -307ms | -37.995
| | P99| 2.417s| 2.35s | -67ms | -2.771
| createDirectChannel | Avg| 777ms| 554ms | -223ms | -28.694
| | P99| 4.031s| 2.406s | -1.625s | -40.310
| createGroupChannel | Avg| 1.28s| 925ms | -355ms | -27.724
| | P99| 7.5s| 4.409s | -3.091s | -41.213
| createPost | Avg| 895ms| 953ms | 58ms | 6.482
| | P99| 4.787s| 4.858s | 71ms | 1.483
| createUser | Avg| 335ms| 280ms | -55ms | -16.415
| | P99| 2.233s| 1.957s | -276ms | -12.358
| deleteDraft | Avg| 15ms| 17ms | 2ms | 13.007
| | P99| 192ms| 199ms | 7ms | 3.643
| deletePost | Avg| 76ms| 137ms | 61ms | 79.820
| | P99| 468ms| 870ms | 402ms | 85.989
| followThreadByUser | Avg| 51ms| 46ms | -5ms | -9.895
| | P99| 240ms| 238ms | -2ms | -0.833
| getAllTeams | Avg| 11ms| 10ms | -1ms | -9.503
| | P99| 154ms| 133ms | -21ms | -13.642
| getCategoriesForTeamForUser | Avg| 45ms| 33ms | -12ms | -26.895
| | P99| 241ms| 238ms | -3ms | -1.247
| getChannel | Avg| 32ms| 24ms | -8ms | -24.818
| | P99| 307ms| 207ms | -100ms | -32.587
| getChannelMember | Avg| 23ms| 22ms | -1ms | -4.327
| | P99| 249ms| 236ms | -13ms | -5.223
| getChannelMembersForTeamForUser | Avg| 14ms| 14ms | 0s | 0.000
| | P99| 165ms| 171ms | 6ms | 3.639
| getChannelStats | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 123ms| 134ms | 11ms | 8.936
| getChannelUnread | Avg| 13ms| 14ms | 1ms | 7.666
| | P99| 160ms| 174ms | 14ms | 8.735
| getChannelsForTeamForUser | Avg| 14ms| 14ms | 0s | 0.000
| | P99| 175ms| 176ms | 1ms | 0.572
| getChannelsForUser | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 103ms| 106ms | 3ms | 2.926
| getClientConfig | Avg| 23ms| 22ms | -1ms | -4.355
| | P99| 246ms| 240ms | -6ms | -2.442
| getDrafts | Avg| 15ms| 16ms | 1ms | 6.796
| | P99| 181ms| 183ms | 2ms | 1.107
| getFilePreview | Avg| 75ms| 77ms | 2ms | 2.678
| | P99| 410ms| 421ms | 11ms | 2.685
| getFileThumbnail | Avg| 58ms| 60ms | 2ms | 3.463
| | P99| 344ms| 359ms | 15ms | 4.362
| getPostThread | Avg| 64ms| 68ms | 4ms | 6.233
| | P99| 492ms| 500ms | 8ms | 1.627
| getPostsForChannel | Avg| 114ms| 126ms | 12ms | 10.522
| | P99| 1.294s| 1.506s | 212ms | 16.389
| getPostsForChannelAroundLastUnread | Avg| 52ms| 53ms | 1ms | 1.910
| | P99| 472ms| 483ms | 11ms | 2.330
| getPreferences | Avg| 11ms| 10ms | -1ms | -9.092
| | P99| 134ms| 121ms | -13ms | -9.706
| getProfileImage | Avg| 86ms| 80ms | -6ms | -7.015
| | P99| 475ms| 473ms | -2ms | -0.421
| getPublicChannelsForTeam | Avg| 34ms| 36ms | 2ms | 5.908
| | P99| 221ms| 229ms | 8ms | 3.622
| getTeamMember | Avg| 14ms| 14ms | 0s | 0.000
| | P99| 199ms| 180ms | -19ms | -9.550
| getTeamMembersForUser | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 152ms| 160ms | 8ms | 5.263
| getTeamStats | Avg| 123ms| 79ms | -44ms | -35.635
| | P99| 472ms| 244ms | -228ms | -48.254
| getTeamsForUser | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 105ms| 97ms | -8ms | -7.641
| getTeamsUnreadForUser | Avg| 17ms| 17ms | 0s | 0.000
| | P99| 217ms| 217ms | 0s | 0.000
| getThreadsForUser | Avg| 16ms| 17ms | 1ms | 6.377
| | P99| 185ms| 193ms | 8ms | 4.324
| getUser | Avg| 16ms| 15ms | -1ms | -6.106
| | P99| 240ms| 229ms | -11ms | -4.591
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 2ms| 3ms | 1ms | 45.888
| | P99| 46ms| 55ms | 9ms | 19.379
| getUsers | Avg| 16ms| 14ms | -2ms | -12.742
| | P99| 231ms| 222ms | -9ms | -3.899
| getUsersByIds | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 49ms| 48ms | -1ms | -2.044
| getUsersByNames | Avg| 13ms| 15ms | 2ms | 14.979
| | P99| 163ms| 179ms | 16ms | 9.820
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 234ms| 194ms | -40ms | -17.113
| | P99| 2.139s| 1.86s | -279ms | -13.043
| logout | Avg| 201ms| 190ms | -11ms | -5.476
| | P99| 2.05s| 883ms | -1.167s | -56.927
| patchPost | Avg| 131ms| 112ms | -19ms | -14.482
| | P99| 990ms| 490ms | -500ms | -50.505
| removeUserCustomStatus | Avg| 405ms| 435ms | 30ms | 7.411
| | P99| 2.194s| 2.233s | 39ms | 1.777
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 41ms| 43ms | 2ms | 4.928
| | P99| 356ms| 362ms | 6ms | 1.685
| searchAllChannels | Avg| 62ms| 62ms | 0s | 0.000
| | P99| 242ms| 240ms | -2ms | -0.825
| searchGroupChannels | Avg| 20ms| 17ms | -3ms | -15.128
| | P99| 178ms| 194ms | 16ms | 9.005
| searchPostsInTeam | Avg| 295ms| 309ms | 14ms | 4.741
| | P99| 2.62s| 3.606s | 986ms | 37.639
| searchUsers | Avg| 58ms| 61ms | 3ms | 5.168
| | P99| 239ms| 241ms | 2ms | 0.835
| setPostReminder | Avg| 60ms| 99ms | 39ms | 64.536
| | P99| 425ms| 860ms | 435ms | 102.353
| unfollowThreadByUser | Avg| 69ms| 55ms | -14ms | -20.349
| | P99| 480ms| 479ms | -1ms | -0.208
| updateCategoriesForTeamForUser | Avg| 306ms| 179ms | -127ms | -41.511
| | P99| 2.14s| 939ms | -1.201s | -56.121
| updatePreferences | Avg| 43ms| 47ms | 4ms | 9.364
| | P99| 391ms| 411ms | 20ms | 5.114
| updateReadStateAllThreadsByUser | Avg| 2ms| 0s | -2ms | -97.653
| | P99| 5ms| 0s | -5ms | -101.010
| updateReadStateThreadByUser | Avg| 147ms| 157ms | 10ms | 6.823
| | P99| 925ms| 955ms | 30ms | 3.242
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 492ms| 508ms | 16ms | 3.250
| | P99| 2.229s| 2.263s | 34ms | 1.525
| upsertDraft | Avg| 17ms| 18ms | 1ms | 5.841
| | P99| 203ms| 205ms | 2ms | 0.984
| viewChannel | Avg| 47ms| 50ms | 3ms | 6.432
| | P99| 444ms| 458ms | 14ms | 3.150
